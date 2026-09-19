<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucw3l7bda"/><circle class="y2d76qgdf"/><circle class="w01xx4bie"/><path class="n41gijbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-emoji-symbols" /></template>
<style>
.n41gijbip {
  fill: currentColor;
  d: path("M15.5 11A2.5 2.5 0 0 0 18 8.5V4h2c.55 0 1-.45 1-1s-.45-1-1-1h-2c-.55 0-1 .45-1 1v3.51c-.42-.32-.93-.51-1.5-.51a2.5 2.5 0 0 0 0 5m-5.05 7.09a.996.996 0 1 0-1.41-1.41l-.71.71l-.71-.71l.35-.35c.98-.98.98-2.56 0-3.54a2.5 2.5 0 0 0-1.77-.73a2.499 2.499 0 0 0-1.77 4.27l.35.35l-1.06 1.06c-.98.98-.98 2.56 0 3.54c.5.48 1.14.72 1.78.72s1.28-.24 1.77-.73l1.06-1.06l.71.71a.996.996 0 1 0 1.41-1.41l-.71-.71zm-4.6-3.89c.12-.12.26-.15.35-.15s.23.03.35.15c.19.2.19.51 0 .71l-.35.35l-.35-.36c-.12-.12-.15-.26-.15-.35s.03-.23.15-.35m0 5.65c-.12.12-.26.15-.35.15s-.23-.03-.35-.15S5 19.59 5 19.5s.03-.23.15-.35l1.06-1.06l.71.71z");
}

.ucw3l7bda {
  fill: currentColor;
  d: path("M10 5H4c-.55 0-1 .45-1 1s.45 1 1 1h2v3c0 .55.45 1 1 1s1-.45 1-1V7h2c.55 0 1-.45 1-1s-.45-1-1-1m0-3H4c-.55 0-1 .45-1 1s.45 1 1 1h6c.55 0 1-.45 1-1s-.45-1-1-1m10.89 11.11a.996.996 0 0 0-1.41 0l-6.36 6.36a.996.996 0 1 0 1.41 1.41l6.36-6.36a.996.996 0 0 0 0-1.41");
}

.w01xx4bie {
  cx: 19.5px;
  cy: 19.5px;
  r: 1.5px;
  fill: currentColor;
}

.y2d76qgdf {
  cx: 14.5px;
  cy: 14.5px;
  r: 1.5px;
  fill: currentColor;
}

</style>
