<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ehmp1dbtn"/><path class="cbo330hbc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:phone-missed-sharp-two-tone" /></template>
<style>
.cbo330hbc {
  d: path("M2 4L2 2L9 2L9 8L7.0953 9.4285C8.5144 12.802 11.198 15.4856 14.5715 16.9047L16 15L22 15L22 22L20 22C10.0589 22 2 13.9411 2 4ZM22.2929 1.7071L15.7071 8.2929M15.7071 1.7071L22.2929 8.2929");
}

.ehmp1dbtn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1 4L1 2C1 1.4477 1.4477 1 2 1L9 1C9.5523 1 10 1.4477 10 2L10 8C10 8.3148 9.8518 8.6111 9.6 8.8L8.3388 9.7459C9.6049 12.3156 11.6844 14.3951 14.2541 15.6612L15.2 14.4C15.3889 14.1482 15.6852 14 16 14L22 14C22.5523 14 23 14.4477 23 15L23 22C23 22.5523 22.5523 23 22 23L20 23C9.5066 23 1 14.4934 1 4Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
