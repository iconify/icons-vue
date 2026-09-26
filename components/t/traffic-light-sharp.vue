<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="smfbkq5iv"/><path class="aefmnnbnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:traffic-light-sharp" /></template>
<style>
.aefmnnbnd {
  fill: currentColor;
  d: path("M13.5 7C13.5 7.8284 12.8284 8.5 12 8.5C11.1716 8.5 10.5 7.8284 10.5 7C10.5 6.1716 11.1716 5.5 12 5.5C12.8284 5.5 13.5 6.1716 13.5 7ZM13.5 12C13.5 12.8284 12.8284 13.5 12 13.5C11.1716 13.5 10.5 12.8284 10.5 12C10.5 11.1716 11.1716 10.5 12 10.5C12.8284 10.5 13.5 11.1716 13.5 12Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.smfbkq5iv {
  d: path("M7 2L17 2L17 17L7 17L7 2ZM8 5L4 5M16 5L20 5M8 10L4 10M16 10L20 10M12 16L12 23");
}

</style>
