<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pvep1hbek"/><path class="a6_8dacep"/><path class="wcg0_nb2l"/><path class="x21bsmbiw"/><path class="pf-164bff"/><path class="hwlfbn0bu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:presentation-graph-broken" /></template>
<style>
.a6_8dacep {
  d: path("M9 10.5L10.2929 9.20711C10.6262 8.87377 10.7929 8.70711 11 8.70711C11.2071 8.70711 11.3738 8.87377 11.7071 9.20711L12.2929 9.79289C12.6262 10.1262 12.7929 10.2929 13 10.2929C13.2071 10.2929 13.3738 10.1262 13.7071 9.79289L15 8.5");
}

.hwlfbn0bu {
  d: path("M4 2V10.5C4 13.5641 4 15.0962 5.00421 16.0481C6.00841 17 7.62465 17 10.8571 17H13.1429C16.3753 17 17.9916 17 18.9958 16.0481C20 15.0962 20 13.5641 20 10.5V10.5V10M20 2V6");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pf-164bff {
  d: path("M14 22L12 21");
}

.pvep1hbek {
  d: path("M2 2H22");
}

.wcg0_nb2l {
  d: path("M12 21L12 17");
}

.x21bsmbiw {
  d: path("M10 22L12 21");
}

</style>
