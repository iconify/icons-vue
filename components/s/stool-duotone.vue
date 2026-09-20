<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="kp80x75nx"/><path class="n9c27ybzk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:stool-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kp80x75nx {
  d: path("M192 40v24a8 8 0 0 1-8 8H72a8 8 0 0 1-8-8V40a8 8 0 0 1 8-8h112a8 8 0 0 1 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n9c27ybzk {
  d: path("M200 64V40a16 16 0 0 0-16-16H72a16 16 0 0 0-16 16v24a16 16 0 0 0 16 16h6.64L56.1 222.75a8 8 0 0 0 6.65 9.15a8 8 0 0 0 1.25.1a8 8 0 0 0 7.89-6.75L79.68 176h96.64l7.78 49.25A8 8 0 0 0 192 232a8 8 0 0 0 1.26-.1a8 8 0 0 0 6.65-9.15L177.36 80H184a16 16 0 0 0 16-16M72 40h112v24H72Zm101.79 120H82.21l12.63-80h66.32Z");
}

</style>
