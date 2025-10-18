# n8n Workflows

Personalized n8n automation workflows for clients.

## Workflows

All client workflows are stored in the `workflows/` folder.

Each workflow is personalized with the client's name and business niche.
```

3. Click **Commit changes**

---

## **Now Create the workflows folder:**

1. Click **Add file** → **Create new file**
2. **Filename:** `workflows/.gitkeep`
3. Click **Commit changes**

---

## **Now Test Your n8n GitHub Node:**

Your GitHub node settings should be:

**Repository Owner:** `jorgeguarnizo2006-gif`

**Repository Name:** `n8n-workflows`

**File Path:** `workflows/{{ $json.filename }}`

**File Content:** `{{ $json.workflow_json }}`

**Commit Message:** `Add workflow for {{ $json.username }}`

**Branch:** `main`

---

## **Run Your Workflow Again**

It should now successfully create the file!

The download URL will be:
```
https://raw.githubusercontent.com/jorgeguarnizo2006-gif/n8n-workflows/main/workflows/stephtradezzz_CallReminder.json
