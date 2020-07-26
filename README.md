# memes
Simple module to fetch memes from a subreddit.

# Example

```ts
import memer from "https://deno.land/x/memes/mod.ts";

const meme = await memer("me_irl");
console.log(`Found ${meme.imageURL}`);

```

# How to run
You need to run your code with `--allow-net` flag.