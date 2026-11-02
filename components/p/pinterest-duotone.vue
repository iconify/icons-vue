<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w0lv7f-we"/><path class="zec67ab0q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pinterest-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.w0lv7f-we {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2.786 8.107C4.936 3.02 10.804.639 15.892 2.788s7.469 8.016 5.32 13.104s-8.016 7.469-13.104 5.32S.637 13.195 2.786 8.107");
}

.zec67ab0q {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m9 20l3-7m-5 1a4.92 4.92 0 0 1 0-4c1.733-3.9 7.267-3.9 9 0a4.924 4.924 0 0 1-5.626 6.794M3 12a9 9 0 1 0 18 0a9 9 0 0 0-18 0");
}

</style>
