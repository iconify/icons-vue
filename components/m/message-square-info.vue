<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jd4d2pv_x"/><path class="afwtzqy0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-info" /></template>
<style>
.afwtzqy0m {
  fill: currentColor;
  d: path("M13 7C13 7.5523 12.5523 8 12 8C11.4477 8 11 7.5523 11 7C11 6.4477 11.4477 6 12 6C12.5523 6 13 6.4477 13 7Z");
  stroke: none;
}

.jd4d2pv_x {
  d: path("M6 3L18 3C19.6569 3 21 4.3431 21 6L21 14C21 15.6569 19.6569 17 18 17L7 17L3 21L3 6C3 4.3431 4.3431 3 6 3ZM12 11L12 13");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
