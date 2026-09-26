<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="p6pu-dv5t"/><path class="nx0emvkfa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:volume-x-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nx0emvkfa {
  d: path("M2 9L6 9L11 4.0019L11 19.9981L6 15L2 15L2 9ZM15.7071 8.7071L22.2929 15.2929M22.2929 8.7071L15.7071 15.2929");
}

.p6pu-dv5t {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 8L5.5859 8L10.293 3.2947C10.923 2.6649 12 3.1111 12 4.0019L12 19.9981C12 20.8889 10.923 21.3351 10.293 20.7053L5.5859 16L2 16C1.4477 16 1 15.5523 1 15L1 9C1 8.4477 1.4477 8 2 8Z");
  stroke: none;
}

</style>
