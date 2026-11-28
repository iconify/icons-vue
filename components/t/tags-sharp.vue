<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="etdy7uq6i"/><path class="d5zm4bcvh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tags-sharp" /></template>
<style>
.d5zm4bcvh {
  fill: currentColor;
  d: path("M12.5 11C12.5 11.8284 11.8284 12.5 11 12.5C10.1716 12.5 9.5 11.8284 9.5 11C9.5 10.1716 10.1716 9.5 11 9.5C11.8284 9.5 12.5 10.1716 12.5 11Z");
  stroke: none;
}

.etdy7uq6i {
  d: path("M6 6L14 6L22 14.8284L14.8284 22L6 14ZM2 10L2 2L10 2");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
