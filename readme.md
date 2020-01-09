## Anki add-on Export Deck to Audio

Code: `2095022381`

Link: [Export deck to audio (Anki 2.1) - AnkiWeb](https://ankiweb.net/shared/info/2095022381)

Add-on này cần phải có `ffmpeg` mới chạy được. Cách cài `ffmpeg` ở bên dưới. Tuy hơi phức tạp, nhưng rất rất đáng công, cả nhà ráng làm.

Sau khi cài được `ffmpeg` rồi thì bật Anki lên sẽ không còn bị lỗi nữa. Bạn nào không cài được thì nên `Disable` cái add-on `Export deck to audio` kia đi.

Cả nhà chịu khó xem video để hiểu về cách sử dụng add-on hay ho này!



## Hướng dẫn cài đặt ffmpeg

### Cài trong Mac:

1. Bật phần mềm Terminal bằng cách:

- Nhấp `⌘ Space`, gõ `terminal`

2. Trong terminal, dán:

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
 - `Enter` và đợi chạy xong (khá là lâu).

3. Dán tiếp:

```
brew install ffmpeg
```
 - Có thể phải chờ rất rất lâu, và đôi lúc cần để ý làm theo hướng dẫn.

### Cài trong Win:

Tham khảo bài viết này: https://m.wikihow.com/Install-FFmpeg-on-Windows

Nhiều bước, nhưng ráng kiên nhẫn, tương lai tương sáng ở cuối đường hầm!