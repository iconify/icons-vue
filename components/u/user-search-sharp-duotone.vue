<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="t7091ltxz"/><path class="ga_l2cbut"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-search-sharp-duotone" /></template>
<style>
.ga_l2cbut {
  d: path("M21 17C21 18.6569 19.6569 20 18 20C16.3431 20 15 18.6569 15 17C15 15.3431 16.3431 14 18 14C19.6569 14 21 15.3431 21 17ZM20.1213 19.1213L20.5 19.5L22 21L22.2929 21.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t7091ltxz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 13C10.3396 13 10.6733 13.0255 11 13.0723V22H2C1.44772 22 1 21.5523 1 21V20C1 16.134 4.13402 13 8 13H10ZM9 3C11.2092 3 13 4.79082 13 7C13 9.20918 11.2092 11 9 11C6.79094 11 5 9.20921 5 7C5 4.79079 6.79094 3 9 3Z");
  stroke: none;
}

</style>
