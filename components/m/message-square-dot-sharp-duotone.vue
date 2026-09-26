<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="s9dzx_b3w"/><path class="ba0j365wv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-dot-sharp-duotone" /></template>
<style>
.ba0j365wv {
  d: path("M21 6C21 7.6569 19.6569 9 18 9C16.3431 9 15 7.6569 15 6C15 4.3431 16.3431 3 18 3C19.6569 3 21 4.3431 21 6Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s9dzx_b3w {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.3431 2L3 2C2.4477 2 2 2.4477 2 3L2 21C2 21.5523 2.4477 22 3 22C3.2652 22 3.5196 21.8946 3.7071 21.7071L7.4142 18L21 18C21.5523 18 22 17.5523 22 17L22 11.6569L20 11.6569C19.3577 11.884 18.6813 12 18 12C14.6863 12 12 9.3137 12 6C12 5.3187 12.116 4.6423 12.3431 4Z");
  stroke: none;
}

</style>
