<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="p54qgbbdy"/><path class="dn9hrcbeq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sunglasses-sharp-duotone" /></template>
<style>
.dn9hrcbeq {
  stroke-opacity: 0.4;
  d: path("M2 13.5L4.2924 7.6512C4.7424 6.601 5.6202 5.7933 6.7041 5.432L8 5L8.154 4.9487M22 13.5L19.7076 7.6512C19.2576 6.601 18.3798 5.7933 17.2959 5.432L16 5L15.846 4.9487M14.2127 15.9743C13.1111 15 10.8889 15 9.7873 15.9743");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p54qgbbdy {
  fill: currentColor;
  d: path("M9.45215 12C10.8449 12 11.8116 13.3882 11.3281 14.6943L9.60449 19.3477C9.45918 19.7397 9.08508 19.9998 8.66699 20H2C1.44772 20 1 19.5523 1 19V13C1 12.4477 1.44772 12 2 12H9.45215ZM22 12C22.5522 12 23 12.4477 23 13V19C23 19.5523 22.5522 20 22 20H15.333C14.9151 19.9997 14.5408 19.7396 14.3955 19.3477L12.6719 14.6943C12.1885 13.3883 13.1554 12.0003 14.5479 12H22Z");
  stroke: none;
}

</style>
