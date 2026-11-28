<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wewj73yns"/><path class="w_5f36b7u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:undo-dot-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w_5f36b7u {
  fill: currentColor;
  d: path("M12.7149 16.9998C12.7149 18.1044 11.8195 18.9998 10.7149 18.9998C9.6103 18.9998 8.7149 18.1044 8.7149 16.9998C8.7149 15.8952 9.6103 14.9998 10.7149 14.9998C11.8195 14.9998 12.7149 15.8952 12.7149 16.9998Z");
  stroke: none;
}

.wewj73yns {
  stroke-opacity: 0.4;
  d: path("M21 17.9998C21 13.9534 18.6274 10.283 14.9378 8.6216C11.2482 6.9602 6.9273 7.6166 3.8975 10.2987M3 6.0002V11H8");
}

</style>
