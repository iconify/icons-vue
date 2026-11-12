<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="an--fmawt"/><path class="p2-28vwqt"/><path class="kdx2-qp7s"/><path class="pjpaztbao"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:watch-round-broken" /></template>
<style>
.an--fmawt {
  d: path("M4.75391 10.0578C5.08272 8.82656 5.73011 7.66266 6.69607 6.6967C9.625 3.76777 14.3737 3.76777 17.3027 6.6967C20.2316 9.62563 20.2316 14.3744 17.3027 17.3033C14.3737 20.2322 9.625 20.2322 6.69607 17.3033C5.73011 16.3373 5.08272 15.1734 4.75391 13.9422");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kdx2-qp7s {
  d: path("M7.02539 6.38745L7.30432 5.13228C7.63801 3.63065 7.80486 2.87983 8.35327 2.43992C8.90167 2 9.6708 2 11.2091 2H12.7917C14.33 2 15.0991 2 15.6475 2.43992C16.1959 2.87983 16.3627 3.63065 16.6964 5.13228L16.9754 6.38745");
}

.p2-28vwqt {
  stroke-linejoin: round;
  d: path("M12 8.92308V12L14 13.9231");
}

.pjpaztbao {
  d: path("M7.02539 17.6123L7.30432 18.8675C7.63801 20.3691 7.80486 21.1199 8.35327 21.5598C8.90168 21.9998 9.67081 21.9998 11.2091 21.9998H12.7917C14.33 21.9998 15.0991 21.9998 15.6475 21.5598C16.1959 21.1199 16.3627 20.3691 16.6964 18.8675L16.9754 17.6123");
}

</style>
