<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz4lj2b2d"/><path class="oi8hf5-0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-assignment-returned" /></template>
<style>
.oi8hf5-0f {
  fill: currentColor;
  d: path("M17 12h-3V8h-4v4H7l5 5zm2-9h-4.18C14.4 1.84 13.3 1 12 1s-2.4.84-2.82 2H5c-.14 0-.27.01-.4.04a2.01 2.01 0 0 0-1.44 1.19c-.1.24-.16.49-.16.77v14c0 .27.06.54.16.78s.25.45.43.64c.27.27.62.47 1.01.55c.13.02.26.03.4.03h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m-7-.25c.41 0 .75.34.75.75s-.34.75-.75.75s-.75-.34-.75-.75s.34-.75.75-.75M19 19H5V5h14z");
}

.xz4lj2b2d {
  fill: currentColor;
  d: path("M5 19h14V5H5zm5-7V8h4v4h3l-5 5l-5-5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
