# 뉴럴노트 개인정보처리방침 · Neural Notes Privacy Policy

마지막 수정: 2026-10-15

**요약: 뉴럴노트는 개인정보를 수집하지 않습니다.** 계정이 없고, 분석 도구·광고·추적이 없고, 개발자가 운영하는 서버도 없습니다. 메모는 이 기기 안에만 있습니다.

**Summary: Neural Notes does not collect personal data.** There is no account, no analytics, no ads and no tracking, and the developer runs no server. Your notes stay on your device.

## 한국어

### 저장하는 것

- 메모 글, 사진, 설정은 앱 안(기기 저장소)에만 저장됩니다. 개발자는 볼 수 없습니다.
- 메모를 잇는 계산(비슷한 메모 찾기, 뜻으로 찾기, 갈래, 지도)은 전부 기기 안에서 합니다. 이 계산을 위해 글을 밖으로 보내지 않습니다.
- Siri로 말한 내용은 Apple이 받아 적습니다(Apple의 방침을 따릅니다). 받아 적은 글과 단축어로 적은 글은 앱을 열 때까지 기기 안의 앱 설정 영역(UserDefaults)에 잠시 보관했다가 메모로 옮깁니다.
- 연결을 치우고 이은 기록으로 연결을 고르는 학습(가지치기)도 기기 안에서 합니다. 학습 기록과 판은 기기 밖으로 나가지 않습니다.
- 잠근 메모는 사용자가 정한 비밀번호로 기기 안에서 암호화합니다. 비밀번호는 저장하지 않으므로 잊으면 되찾을 수 없습니다. 비밀번호 힌트는 암호화하지 않습니다.

### 기기 밖으로 나가는 것

**링크 제목 알아보기** 하나뿐이며, 처음부터 켜져 있습니다. 메모에 아래 사이트의 링크가 들어 있으면 — 직접 붙였든, 백업을 되살렸든, 파일을 가져왔든, Siri로 적었든 — 제목을 보여 주려고 그 사이트의 공개 API에 링크 주소(또는 그 안의 식별자)를 보냅니다. 링크마다 한 번 묻습니다. 사이트가 제목을 주지 않으면 하루 뒤에, 연결이 안 됐으면 다음에 다시 묻고, 설정을 껐다 켜면 처음부터 다시 묻습니다.

| 붙인 링크 | 요청을 받는 곳 |
| --- | --- |
| YouTube | www.youtube.com |
| Vimeo | vimeo.com |
| Spotify | open.spotify.com |
| SoundCloud | soundcloud.com |
| GitHub | api.github.com |
| Wikipedia | 해당 언어의 wikipedia.org |
| arXiv | api.openalex.org (OpenAlex, 논문 정보 제공 기관) |
| Hacker News | hacker-news.firebaseio.com |
| TikTok | www.tiktok.com |

- 보내는 것은 링크 주소(또는 그 식별자)뿐입니다. 메모 글이나 기기 식별자는 보내지 않고, 리퍼러도 붙이지 않습니다.
- 모든 인터넷 요청처럼, 요청을 받는 사이트는 기기의 IP 주소, 앱의 사용자 에이전트(User-Agent), 기기 언어 설정을 볼 수 있습니다.
- 각 사이트는 자기 개인정보처리방침에 따라 요청을 처리합니다.
- **설정 → 링크 제목 알아보기**를 끄면 이 요청도 멈추고, 받아 둔 제목도 지웁니다.
- 메모 속 링크를 누르면 Safari 등 기기의 기본 앱에서 열립니다.

### 백업

설정에서 **백업 내보내기**(웹에서는 **백업 파일로 저장**)를 누르면 메모를 파일 하나로 만듭니다. 그 파일을 어디에 둘지는 사용자가 고르며, 앱이 따로 올리지 않습니다.

### 다른 앱에서 가져오기

ChatGPT·Claude·Grok·노션 내보내기 파일, 애플 메모 단축어, 마크다운 파일은 **기기 안에서** 풉니다. 파일을 어디에도 보내지 않습니다.

- 가져오기 전에 미리보기로 무엇이 들어오는지 보여 주고, 사용자가 고른 것만 저장합니다.
- 단축어 「뉴럴노트로 가져오기」로 넘긴 파일은 앱 안의 받은 편지함 폴더에 잠시 두었다가, 미리보기에서 가져오거나 취소하면 지웁니다. 그 전에 앱이 꺼지면 다음에 켤 때 미리보기가 다시 뜹니다.
- Claude 내보내기에 든 프로젝트(지침·지식 파일)와 「Claude가 기억하는 나」(Claude가 대화에서 추려 둔 사용자 정보)도 메모 후보로 보이지만, 기본으로 고르지 않고 한꺼번에 고르기에도 들지 않습니다. 계정 정보 파일(`users.json`, 이메일·전화번호)은 읽지 않습니다.
- 가져온 메모에는 어디서 왔는지(예: 대화 id)를 함께 적어, 다시 가져올 때 같은 글이 두 번 생기지 않게 합니다. 이 표시도 메모와 같이 기기 안에만 있습니다.

### 지우기

앱을 지우면 앱 안의 메모·사진·설정도 함께 지워집니다. 휴지통의 메모는 설정에서 비울 수 있습니다.

### 어린이

누구의 정보도 수집하지 않으므로 어린이의 정보도 수집하지 않습니다.

### 바뀔 때

이 방침이 바뀌면 이 페이지의 날짜를 고칩니다.

### 문의

renewye21@gmail.com

## English

### What stays on your device

- Notes, photos and settings are stored only inside the app on your device. The developer cannot see them.
- Everything that connects your notes (similar notes, search by meaning, strands, the map) is computed on the device. Your writing is never sent anywhere for this.
- What you say to Siri is transcribed by Apple under Apple's privacy policy. Text you capture with Siri or Shortcuts waits in the app's on-device settings storage (UserDefaults) until you next open the app, then becomes a note.
- Learning which connections you prefer (from the connections you remove or add) also happens on the device. The learning log and its checkpoints never leave it.
- Locked notes are encrypted on the device with a password you choose. The password is not stored, so it cannot be recovered if you forget it. The password hint is not encrypted.

### What else leaves your device

Only **link titles**, which is on by default. When a note contains a link from one of the sites below — typed, pasted, restored from a backup, imported, or captured with Siri — the app sends that link's address (or the identifier inside it) to the site's public API to show its title. Each link is asked once. If the site returns no title it is retried after a day, if the connection failed it is retried next time, and turning the setting off and on asks again from scratch.

| Pasted link | Request goes to |
| --- | --- |
| YouTube | www.youtube.com |
| Vimeo | vimeo.com |
| Spotify | open.spotify.com |
| SoundCloud | soundcloud.com |
| GitHub | api.github.com |
| Wikipedia | the matching language's wikipedia.org |
| arXiv | api.openalex.org (OpenAlex, a scholarly metadata service) |
| Hacker News | hacker-news.firebaseio.com |
| TikTok | www.tiktok.com |

- Only the link address (or its identifier) is sent. No note text, no device identifier, and no referrer.
- As with any internet request, the receiving site can see your device's IP address, the app's user agent and your device language.
- Each site handles the request under its own privacy policy.
- Turn off **Settings → Look up link titles** to stop these requests and clear saved titles.
- Tapping a link in a note opens it in Safari or your default app.

### Backups

**Export backup** in Settings (**Back up to a file** on the web) writes your notes to a single file. You choose where that file goes; the app uploads nothing.

### Importing from other apps

Export files from ChatGPT, Claude, Grok and Notion, the Apple Notes shortcut, and Markdown files are read **on your device**. They are not sent anywhere.

- A preview shows what will come in, and only what you choose is saved.
- A file handed over with the "Import into Neural Notes" shortcut waits in an inbox folder inside the app and is deleted once you import or cancel in the preview. If the app closes before that, the preview comes back next time.
- Claude projects (instructions, knowledge files) and "What Claude remembers about me" (what Claude summarised about you from chats) show up as candidates too, but they start unselected and "Pick all" leaves the memory out. The account file (`users.json`, email and phone) is never read.
- Imported notes keep a note of where they came from (for example a conversation id) so importing again does not create duplicates. That stays with the note, on your device.

### Deleting

Deleting the app deletes its notes, photos and settings. You can empty the trash in Settings.

### Children

The app collects no one's data, including children's.

### Changes

If this policy changes, the date at the top of this page changes.

### Contact

renewye21@gmail.com
