---
title: test new editor
date: 2022-06-18 23:06:00 +0300
thumbnail: https://i.pinimg.com/736x/70/2a/65/702a65b68102d0d865c851898da321b8.jpg
pin: false
tags:
  - shrek
  - meme
toc: true
comments: true
math: false
mermaid: false
---
# hello world

## abc

abc

[Default Button Text](https://www.youtube.com/watch?v=dQw4w9WgXcQ){: .btn}
[Primary Button Text](https://www.youtube.com/watch?v=dQw4w9WgXcQ){: .btn .btn--primary}
[Success Button Text](https://www.youtube.com/watch?v=dQw4w9WgXcQ){: .btn .btn--success}
[Warning Button Text](https://www.youtube.com/watch?v=dQw4w9WgXcQ){: .btn .btn--warning}
[Danger Button Text](https://www.youtube.com/watch?v=dQw4w9WgXcQ){: .btn .btn--danger}
[Info Button Text](https://www.youtube.com/watch?v=dQw4w9WgXcQ){: .btn .btn--info}
[Inverse Button](https://www.youtube.com/watch?v=dQw4w9WgXcQ){: .btn .btn--inverse}
[Light Outline Button](https://www.youtube.com/watch?v=dQw4w9WgXcQ){: .btn .btn--light-outline}

# test

123

{% include button.html button_name="My Button" button_class="primary" button_href="https://www.youtube.com/watch?v=dQw4w9WgXcQ" %}

test

```python
def smart_rename(file):
    # renames a file by adding a numeric index to it
    # increments the index if the directory already has files with the index
    regex = r'(.+)_\((\d+)\)\.(.+)' # filename_(0).ext
    make_filename = lambda p: p[0] + f"_({p[1]})." + p[2]
    filename, path = os.path.basename(file), os.path.dirname(file)
    match = match_regex(regex, filename)
    parts = list(match.groups())[::2] if match else filename.split('.')
    parts.insert(1, int(match.group(2)) if match else 0)
    new_path = os.path.join(path, make_filename(parts))
    while os.path.exists(new_path):
        parts[1] += 1
        new_path = os.path.join(path, make_filename(parts))
    return new_path
```

gfsghfghs

* shghsg
* sg
* h
* sgfh
* sf
* hg
* fh
* fsg

![shg](/assets/uploads/сегодня-не-среш.jpg "gsh")
