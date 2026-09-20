<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="shbmqcbzn"/><path class="ma6vduhrr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:umbrella-simple-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ma6vduhrr {
  d: path("M240 126.63A112.44 112.44 0 0 0 51.75 53.75a111.56 111.56 0 0 0-35.7 72.88A16 16 0 0 0 32 144h88v56a32 32 0 0 0 64 0a8 8 0 0 0-16 0a16 16 0 0 1-32 0v-56h88a16 16 0 0 0 16-17.37M32 128a96.43 96.43 0 0 1 161.4-62.48A95.32 95.32 0 0 1 224 128Z");
}

.shbmqcbzn {
  d: path("M224 136H32a8 8 0 0 1-8-8.71a104.37 104.37 0 0 1 207.94 0A8 8 0 0 1 224 136");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
