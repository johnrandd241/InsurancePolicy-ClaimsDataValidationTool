# InsurancePolicy-ClaimsDataValidationTool
Designed a prototype validation system to ensure data accuracy between insurance policy and claims databases. The tool flagged mismatches between claim payouts and policy limits, missing policyholder information, and inconsistent date formats across systems.

This project validates insurance claims by checking:
- If the policy is active
- If the claim amount exceeds the coverage limit
- If the claim date is within the policy’s coverage period

## 🔧 How It Works
1. Reads `claims.csv` and `policies.csv`
2. Merges the two datasets
3. Applies validation rules
4. Exports results to `validated_claims_report.xlsx`

## 🛠 Tech Stack
- Python
- Pandas
- Excel

## 🚀 Run It
```bash
python insurance_claim_validator.py
