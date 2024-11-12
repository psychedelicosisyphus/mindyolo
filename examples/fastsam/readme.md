# Fast Segment Anything
## <a name="GettingStarted"></a> Getting Started


First download a [model checkpoint](#model-checkpoints).

Then, you can run the scripts to try the everything mode and three prompt modes.

```shell
# Everything mode
python ./examples/fastsam/Inference.py --config ./configs/fastsam/fastsam-x.yaml --weight=./pth2ckpt-fastsamx.ckpt --image_path ./examples/fastsam/images/cat.jpg
```

```shell
# Text prompt
coming soon
```

```shell
# Box prompt (xywh)
coming soon
```

```shell
# Points prompt
coming soon
```