<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="im5nknbmw"/><path class="xrihfs7pj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:split-horizontal-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.im5nknbmw {
  d: path("m232 128l-32 32V96ZM56 160V96l-32 32Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xrihfs7pj {
  d: path("M104 40a8 8 0 0 0-8 8v72H64V96a8 8 0 0 0-13.66-5.66l-32 32a8 8 0 0 0 0 11.32l32 32A8 8 0 0 0 64 160v-24h32v72a8 8 0 0 0 16 0V48a8 8 0 0 0-8-8M48 140.69L35.31 128L48 115.31Zm189.66-18.35l-32-32A8 8 0 0 0 192 96v24h-32V48a8 8 0 0 0-16 0v160a8 8 0 0 0 16 0v-72h32v24a8 8 0 0 0 13.66 5.66l32-32a8 8 0 0 0 0-11.32M208 140.69v-25.38L220.69 128Z");
}

</style>
