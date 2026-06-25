# OpusChat Setup

This page mirrors the public OpusChat website flow and adds one practical preparation step for heavy Cursor users.

## What You Need

Before using OpusChat, prepare:

1. A Cursor installation.
2. The OpusChat `.vsix` extension file.
3. An OpusChat license key.
4. A dedicated Cursor Pro account for heavy AI coding sessions.

## Why Use A Dedicated Cursor Pro Account?

For long AI coding sessions, do not use your main personal Cursor account if you care about keeping that account clean and separate from experiments.

Use a dedicated Pro account that you are comfortable retiring later if you stop using this workflow.

If you do not already have a spare Pro account, support may provide one for $15/month.

Contact:

Telegram: @joejoeCoffe

## Step 1: Get A License

Choose a duration on the pricing page:

https://opuschat.pingmufanyi.top/pricing.html

Plans:

- Day Pass: $10
- Week Pass: $60
- Month Pass: $260

After payment, you receive a license key instantly.

Important: the license timer starts only on first activation.

## Step 2: Download The Extension

Download the `.vsix` file:

https://opuschat.pingmufanyi.top/download.html

## Step 3: Install In Cursor

Two install options:

### Option A: Cursor UI

1. Open Cursor.
2. Open Command Palette.
3. Run `Extensions: Install from VSIX...`.
4. Select the downloaded `.vsix` file.
5. Restart Cursor.

### Option B: Terminal

```bash
cursor --install-extension opus-chat-panel.vsix
```

Then restart Cursor.

## Step 4: Activate

Open the OpusChat panel in Cursor and paste your license key.

Activation notes:

- The timer starts only on first activation.
- One device can be bound at a time.
- You can re-activate on a new device to transfer the binding.

## Step 5: Start With A Small Task

For the first run, use a small coding task:

- Ask one agent to inspect a file.
- Ask another agent to summarize next steps.
- Confirm the panel is working before starting a long session.

After that, you can use OpusChat for longer Cursor AI coding sessions.
