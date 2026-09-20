<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="u-aq4vbqo"/><path class="m9ftgcbgm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:t-shirt-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.m9ftgcbgm {
  d: path("M247.59 61.22L195.83 33a8 8 0 0 0-3.83-1h-32a8 8 0 0 0-8 8a24 24 0 0 1-48 0a8 8 0 0 0-8-8H64a8 8 0 0 0-3.84 1L8.41 61.22a15.76 15.76 0 0 0-6.59 21.26l19.27 36.81A16.37 16.37 0 0 0 35.67 128H56v80a16 16 0 0 0 16 16h112a16 16 0 0 0 16-16v-80h20.34a16.37 16.37 0 0 0 14.58-8.71l19.27-36.81a15.76 15.76 0 0 0-6.6-21.26M35.67 112a.62.62 0 0 1-.41-.13L16.09 75.26L56 53.48V112ZM184 208H72V48h16.8a40 40 0 0 0 78.38 0H184Zm36.75-96.14a.55.55 0 0 1-.41.14H200V53.48l39.92 21.78Z");
}

.u-aq4vbqo {
  d: path("m247.11 78.77l-19.27 36.81a8.44 8.44 0 0 1-7.5 4.42H192V40l51.78 28.25a7.81 7.81 0 0 1 3.33 10.52m-238.22 0l19.27 36.81a8.44 8.44 0 0 0 7.5 4.42H64V40L12.22 68.25a7.81 7.81 0 0 0-3.33 10.52");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
