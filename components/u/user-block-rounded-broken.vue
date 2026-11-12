<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="dtl23o_xq"/><path class="uwas5gbbp"/><circle class="ez1x61b2a"/><path class="o_socdebe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-block-rounded-broken" /></template>
<style>
.dtl23o_xq {
  cx: 12px;
  cy: 6px;
  r: 4px;
}

.ez1x61b2a {
  cx: 18px;
  cy: 18px;
  r: 3px;
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o_socdebe {
  d: path("M13 20.9595C12.6734 20.9862 12.3395 21 12 21C8.13401 21 5 19.2091 5 17C5 16.6547 5.07657 16.3196 5.22053 16M14.5 13.2626C13.7236 13.093 12.8808 13 12 13C10.9264 13 9.90926 13.1381 9 13.3849");
}

.uwas5gbbp {
  d: path("M20.1211 15.8787L15.8786 20.1213");
}

</style>
