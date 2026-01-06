# Lead Scorer

**Type:** lead_scorer
**Description:** Scores and qualifies leads based on ICP fit

## Configuration
- Business: Simple Flo Solutions
- Target Customer: small service businesses
- Trigger: webhook
- Tools: web_search, crm_access

## Deploy to Railway
1. Create new GitHub repo
2. Push this directory
3. Deploy to Railway
4. Add ANTHROPIC_API_KEY env variable

## Test Locally
```bash
export ANTHROPIC_API_KEY='your_key'
python agent.py
```

## Webhook URL
After deployment: `https://your-app.railway.app/run`

## Example Request
```bash
curl -X POST https://your-app.railway.app/run \
  -H "Content-Type: application/json" \
  -d '{"input": "test"}'
```
