<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kdx2-qp7s"/><path class="s0ay1abnm"/><path class="w37drss5a"/><path class="p2-28vwqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:watch-round-linear" /></template>
<style>
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

.s0ay1abnm {
  d: path("M7.02539 17.6125L7.30432 18.8677C7.63801 20.3694 7.80486 21.1202 8.35327 21.5601C8.90168 22 9.67081 22 11.2091 22H12.7917C14.33 22 15.0991 22 15.6475 21.5601C16.1959 21.1202 16.3627 20.3694 16.6964 18.8677L16.9754 17.6126");
}

.w37drss5a {
  d: path("M19.5 12C19.5 16.1421 16.1421 19.5 12 19.5C7.85786 19.5 4.5 16.1421 4.5 12C4.5 7.85786 7.85786 4.5 12 4.5C16.1421 4.5 19.5 7.85786 19.5 12Z");
}

</style>
