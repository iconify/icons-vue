<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="wrc6tm74h"/><path class="p9760fzsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p9760fzsb {
  d: path("M14.2929 14.2929L21.2929 21.2929");
}

.wrc6tm74h {
  fill: currentColor;
  d: path("M18 10C18 14.2802 14.2802 18 10 18C5.7198 18 2 14.2802 2 10C2 5.7198 5.7198 2 10 2C14.2802 2 18 5.7198 18 10Z");
  stroke: none;
}

</style>
