# thabat-media

Public media for Thabat's social posts: the rendered videos and swipe slides that Metricool
publishes to Instagram and TikTok. **Everything here is public.** Never put anything private here.

The sources (scripts, storyboards, voice takes, post text) live in the private app repository under
`marketing/`; this repository holds only the finished files, so each one has a public link that
Metricool can fetch.

## Layout

One folder per post, named after its folder in the app repository:

```
<slug>/
  <slug>.mp4          a video (with cover.jpg)
  cover.jpg
  instagram-01.jpg …  a swipe post, Instagram 4:5
  tiktok-01.jpg …     the same slides on a 9:16 ground
```

Public link to a file:
`https://raw.githubusercontent.com/mahmudkg/thabat-media/main/<slug>/<file>`

Files are never deleted or replaced once posted: this is the archive of what went out.
GitHub refuses single files over 100 MB.
