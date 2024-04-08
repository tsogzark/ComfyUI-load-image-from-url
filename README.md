A simple node to load image from local path or http url.

![](https://i.postimg.cc/XY0CLx3Q/image.png)

```json
{
  "last_node_id": 2,
  "last_link_id": 1,
  "nodes": [
    {
      "id": 2,
      "type": "PreviewImage",
      "pos": [
        1103,
        -359
      ],
      "size": [
        241.4442291259768,
        243.02276031494148
      ],
      "flags": {},
      "order": 1,
      "mode": 0,
      "inputs": [
        {
          "name": "images",
          "type": "IMAGE",
          "link": 1
        }
      ],
      "properties": {
        "Node name for S&R": "PreviewImage"
      }
    },
    {
      "id": 1,
      "type": "LoadImageFromUrlOrPath",
      "pos": [
        570,
        -360
      ],
      "size": {
        "0": 400,
        "1": 200
      },
      "flags": {},
      "order": 0,
      "mode": 0,
      "outputs": [
        {
          "name": "IMAGE",
          "type": "IMAGE",
          "links": [
            1
          ],
          "shape": 3,
          "slot_index": 0
        },
        {
          "name": "MASK",
          "type": "MASK",
          "links": null,
          "shape": 3
        }
      ],
      "properties": {
        "Node name for S&R": "LoadImageFromUrlOrPath"
      },
      "widgets_values": [
        "https://i.postimg.cc/TYbdk63X/test.png"
      ]
    }
  ],
  "links": [
    [
      1,
      1,
      0,
      2,
      0,
      "IMAGE"
    ]
  ],
  "groups": [],
  "config": {},
  "extra": {},
  "version": 0.4
}
```