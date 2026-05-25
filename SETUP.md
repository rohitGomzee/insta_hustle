# Insta_Hustle - Setup & Tool Requirements

## Current Status

### ✅ Available Tools
- **Video Generation:** Multiple providers (fal.ai, Runway, Google Veo, OpenAI Sora, Minimax, etc.)
- **Voice:** ElevenLabs (check existing OpenClaw setup)
- **Workspace:** Folder structure created

### ❌ Blocked - Need API Keys/Setup

**For Realistic AI Human Videos (face + voice + lip-sync):**

1. **HeyGen API** (Best for talking head)
   - Website: heygen.com
   - Pricing: ~$30-100/month for API access
   - Why: Best lip-sync, natural expressions, avatar consistency
   - Alternative: D-ID (d-id.com)

2. **ElevenLabs** (Voice)
   - Check if already configured in OpenClaw
   - If not: elevenlabs.io, ~$5-22/month

3. **Fallback Option - Local/Open Source**
   - SadTalker (GitHub) - free but requires GPU + setup
   - Wav2Lip - lip-sync only
   - More complex, less polished

## Recommended Stack for 3-4 Videos/Day

**Option A - Paid APIs (Recommended for quality):**
- HeyGen API: Avatar + video generation
- ElevenLabs: Voice (if not using HeyGen's built-in)
- Cost: ~$50-150/month
- Output: Professional, consistent, fast

**Option B - Hybrid:**
- Generate avatar images (free/cheap)
- Use Fal.ai/Runway for video from images
- ElevenLabs for voice
- Cost: ~$30-80/month
- Output: Good, but less consistent character

**Option C - Local/Open Source:**
- SadTalker + ElevenLabs
- Cost: Free + voice API
- Output: Variable quality, requires technical setup

## What I Need From You

1. **Which option?** (A recommended for speed/quality)
2. **API Keys:**
   - HeyGen API key (if Option A)
   - ElevenLabs API key (if not in OpenClaw)
   - Or: Fal.ai / Runway API key (if Option B)

3. **Avatar preferences:**
   - Age range? (25-35?)
   - Style? (professional, casual, friendly?)
   - Outfit? (business, smart casual?)
   - Background? (studio, office, neutral?)

## Next Steps Once We Have Keys

1. Generate consistent avatar (3-5 reference images)
2. Test video pipeline with sample script
3. Build content research engine
4. Create first 3-4 videos
5. Set up daily automation workflow

---

**Note:** Image generation currently blocked (billing limits on Google/OpenAI). We can work around this with HeyGen's built-in avatars or use alternative image providers.
