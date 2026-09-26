<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ztsnvwd_n"/><path class="z9i4rfbjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tablet-vertical" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z9i4rfbjq {
  fill: currentColor;
  d: path("M8.5 13.5C9.3284 13.5 10 12.8284 10 12C10 11.1716 9.3284 10.5 8.5 10.5C7.6716 10.5 7 11.1716 7 12C7 12.8284 7.6716 13.5 8.5 13.5Z");
  stroke: none;
}

.ztsnvwd_n {
  d: path("M17 22H7C5.3431 22 4 20.6569 4 19V5C4 3.3432 5.3431 2 7 2H17C18.6569 2 20 3.3432 20 5V19C20 20.6569 18.6569 22 17 22Z");
}

</style>
