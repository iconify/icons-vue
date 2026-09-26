<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ag6j5y4_q"/><path class="nu2b7cc2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-sharp-duotone" /></template>
<style>
.ag6j5y4_q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 10C18 14.2802 14.2802 18 10 18C5.7198 18 2 14.2802 2 10C2 5.7198 5.7198 2 10 2C14.2802 2 18 5.7198 18 10Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nu2b7cc2b {
  d: path("M14.9497 14.9497L21.2929 21.2929");
}

</style>
