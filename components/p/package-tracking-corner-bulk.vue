<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ob0z2s13d"/><path class="sy3zhcbmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-tracking-corner-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ob0z2s13d {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4.106 5.553C4.643 4.478 5.652 3.001 7 3h10c1.348.001 2.357 1.478 2.894 2.553l1 2A1 1 0 0 1 20 9H9v11a1 1 0 0 1-1 1H6a3 3 0 0 1-3-3V8c0-.155.036-.308.106-.447Zm10.707 14.658a33 33 0 0 1-1.322-1.435C12.878 18.061 12 16.985 12 16a5 5 0 0 1 10 0c0 .985-.878 2.061-1.491 2.776q-.64.737-1.322 1.435c-.488.504-.984 1-1.48 1.496a1 1 0 0 1-1.414 0c-.496-.496-.992-.992-1.48-1.496M16 16a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

.sy3zhcbmn {
  d: path("M20 7a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Zm-5.187 13.211a33 33 0 0 1-1.322-1.435C12.878 18.061 12 16.985 12 16a5 5 0 0 1 10 0c0 .985-.878 2.061-1.491 2.776q-.64.737-1.322 1.435c-.488.504-.984 1-1.48 1.496a1 1 0 0 1-1.414 0c-.496-.496-.992-.992-1.48-1.496M17 19.583c.681-.686 1.361-1.375 1.991-2.109c.291-.339.578-.689.811-1.072c.077-.127.166-.267.198-.414v-.002a3 3 0 0 0-6 0v.002c.032.147.121.287.198.414c.233.383.52.733.811 1.072c.63.734 1.31 1.423 1.991 2.109");
}

</style>
