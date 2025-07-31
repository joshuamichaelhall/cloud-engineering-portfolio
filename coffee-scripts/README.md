# ☕ Daily Coffee Scripts

## What Are Coffee Scripts?

Every morning at 5:15 AM, I write a small Python script that solves a real AWS problem. These 15-minute exercises help me:
- Build practical AWS automation skills
- Create portfolio pieces that demonstrate real value
- Start each day with a concrete win
- Build a library of reusable solutions

## Script Categories

### Cost Optimization
- Scripts that find and eliminate AWS waste
- Resource rightsizing recommendations
- Unused resource cleanup

### Security & Compliance
- Security group audits
- IAM policy analysis
- Encryption verification
- Compliance checking

### Automation & Efficiency
- Backup automation
- Deployment helpers
- Monitoring setup
- Tag enforcement

### Infrastructure Management
- Resource inventory
- Cross-region operations
- Disaster recovery testing
- Performance optimization

## Featured Scripts

### August 2025
- `2025-08-05_ec2_cost_analyzer.py` - Analyzes EC2 usage and recommends savings
- `2025-08-06_s3_encryption_audit.py` - Finds unencrypted S3 buckets
- `2025-08-07_unused_ebs_finder.py` - Identifies unattached EBS volumes

## How to Use These Scripts

1. Each script is self-contained and runnable
2. Requires AWS credentials configured
3. Most scripts use boto3 (AWS SDK for Python)
4. Include error handling and logging
5. Designed to be safe (read-only unless specified)

## Script Template

```python
#\!/usr/bin/env python3
"""
Daily Coffee Script: [Date]
Purpose: [What problem does this solve?]
Time to build: 15 minutes
Potential savings: $[X]/month
"""

import boto3
from datetime import datetime

def main():
    """Main function"""
    # Your automation here
    pass

if __name__ == "__main__":
    main()
```

## Running the Scripts

```bash
# Install dependencies
pip install boto3

# Configure AWS credentials
aws configure

# Run a script
python 2025-08-05_ec2_cost_analyzer.py
```

## Contributing Ideas

Have a repetitive AWS task that could be automated? Open an issue with your idea\!

---

*New script added every weekday morning\!*
EOF < /dev/null