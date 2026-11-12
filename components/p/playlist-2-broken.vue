<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f-nfw68nc"/><path class="k6_m8bb3p"/><path class="rvg1ddc-m"/><path class="hi5e58bpt"/><path class="olcvaabye"/><path class="k3tmy3scv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:playlist-2-broken" /></template>
<style>
.f-nfw68nc {
  d: path("M16 16.4286C16 17.8487 14.8807 19 13.5 19C12.1193 19 11 17.8487 11 16.4286C11 15.0084 12.1193 13.8571 13.5 13.8571C14.8807 13.8571 16 15.0084 16 16.4286ZM16 16.4286V10");
}

.hi5e58bpt {
  d: path("M8 17H3");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k3tmy3scv {
  d: path("M13 9L6.82353 9M4.32353 9H3");
}

.k6_m8bb3p {
  d: path("M16.9205 7.95812L18.675 7.11595C19.4652 6.73668 19.8603 6.54705 20.1799 6.60553C20.4327 6.65176 20.6579 6.79348 20.8089 7.00132C21 7.26422 21 7.70244 21 8.57889C21 8.95791 21 9.14742 20.9395 9.31341C20.8909 9.44661 20.8145 9.56796 20.7155 9.6694C20.592 9.7958 20.4212 9.87781 20.0795 10.0418L18.325 10.884C17.5348 11.2633 17.1397 11.4529 16.8201 11.3944C16.5673 11.3482 16.3421 11.2065 16.1911 10.9986C16 10.7357 16 10.2975 16 9.42106C16 9.04203 16 8.85252 16.0605 8.68654C16.1091 8.55334 16.1855 8.43199 16.2845 8.33055C16.408 8.20414 16.5788 8.12213 16.9205 7.95812Z");
}

.olcvaabye {
  d: path("M3 5H10.4118M13.4118 5H15");
}

.rvg1ddc-m {
  d: path("M9 13H3");
}

</style>
