<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cxv0e2blx"/><path class="i5bv225ul"/><circle class="dtl23o_xq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-hand-up-line-duotone" /></template>
<style>
.cxv0e2blx {
  stroke-linejoin: round;
  d: path("M20 21.5L19.3505 15.9795C19.1506 14.2804 17.7107 13 16 13H8C5 13 3.06717 10.2687 2.38197 7.52787L2 6");
}

.dtl23o_xq {
  cx: 12px;
  cy: 6px;
  r: 4px;
}

.i5bv225ul {
  d: path("M16 13V18C16 19.8856 16 20.8284 15.4142 21.4142C14.8284 22 13.8856 22 12 22C10.1144 22 9.17157 22 8.58579 21.4142C8 20.8284 8 19.8856 8 18V13");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
