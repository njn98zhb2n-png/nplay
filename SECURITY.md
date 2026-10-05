# NPlay Security

Never commit Supabase secret/service-role keys, passwords, private API keys, or user exports. The browser may contain only the Supabase publishable key.

Before real youth/family data is onboarded: verify email confirmation, strong password settings, auth rate limits/CAPTCHA, exact redirect allow-list, RLS on every exposed table, and test anonymous/coach/guardian/unrelated-team access. Keep youth data private by default.

NPlay is not production-security-approved until the RLS adversarial test matrix passes.
