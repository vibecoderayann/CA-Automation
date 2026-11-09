# Contributing to CA Copilot

Thank you for your interest in contributing to **CA Copilot**! We welcome contributions from Chartered Accountants, auditors, finance professionals, and software engineers to build the best offline-first accounting and audit automation suite.

---

## 🌟 Ways You Can Contribute

1. **Audit & Statutory Domain Knowledge**:
   - Provide feedback on ICAI standards (SA 230, SA 505, SA 530, Guidance Notes).
   - Suggest clauses for Income Tax Form 3CD, GST notifications, and MSME 43B(h) compliance.
   - Share edge cases in tally ledger formats, bank statement layouts, and GSTR-2B JSON schemas.

2. **Code & Engineering**:
   - Improve parsing performance for massive Excel/CSV workbooks (>500k rows).
   - Add new audit verification algorithms or heuristic anomaly checks.
   - Enhance the Electron desktop experience and UI workflows.

3. **Bug Reports & Feature Requests**:
   - Submit clear, reproducible bug reports via [GitHub Issues](https://github.com/vibecoderayann/CA-Automation/issues).

---

## 🛠️ Local Development Setup

### Prerequisites
- **Node.js**: `v20.0.0` or higher
- **npm**: `v10.0.0` or higher
- **Git**

### Steps

```bash
# 1. Fork the repo and clone your fork:
git clone https://github.com/vibecoderayann/CA-Automation.git
cd CA-Automation

# 2. Install dependencies:
npm install

# 3. Start the Vite development server:
npm run dev

# 4. Start Electron desktop dev mode:
npm run electron:dev

# 5. Run the full test suite:
npm run test:all
```

---

## 📋 Pull Request (PR) Guidelines

1. **Branch Naming**:
   - `feat/feature-name` for new features
   - `fix/bug-fix` for bug fixes
   - `docs/documentation-update` for documentation changes

2. **Test Coverage**:
   - Ensure all automated unit and statutory engine tests pass before opening a PR:
     ```bash
     npm run test:all
     ```

3. **Data Privacy First**:
   - **Never commit real client data**, financial figures, confidential GSTINs, or private keys into test suites or sample files. Always use synthetic/mocked data.

---

## 📜 Code of Conduct

Please review and adhere to our [Code of Conduct](CODE_OF_CONDUCT.md) in all community interactions.

Thank you for helping us empower Chartered Accountants with open, privacy-first automation!
