# GPTアイコン

Custom GPTのアバターに使うアイコン。

| ファイル | GPT |
| --- | --- |
| `guardian.svg` / `guardian.png` | がんこな門番（案A） |
| `story.svg` / `story.png` | きみが主人公のぼうけん（案C） |

- **GPTに設定するときは `.png` をアップロードする**（512x512。GPTが円形に切り抜く）
- 元データはSVG。作り直すときはSVGを編集してPNGに書き出す:
  ```
  rsvg-convert -w 512 -h 512 guardian.svg -o guardian.png
  rsvg-convert -w 512 -h 512 story.svg    -o story.png
  ```
- 中央に主役・太い輪郭・高コントラストで、小さい円形表示でも判別できるようにしてある。
