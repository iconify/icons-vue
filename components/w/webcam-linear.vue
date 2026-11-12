<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qgu7_ebsb"/><path class="kva043bzk"/><path class="t26d7g3rg"/><path class="pf1ifwbeb"/><path class="y-9fctbqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:webcam-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kva043bzk {
  d: path("M16 22H8");
}

.pf1ifwbeb {
  d: path("M12 13C10.3431 13 9 11.6569 9 10C9 8.34315 10.3431 7 12 7C13.6569 7 15 8.34315 15 10C15 11.6569 13.6569 13 12 13Z");
}

.qgu7_ebsb {
  stroke-linejoin: round;
  d: path("M12 4.50049H12.0001");
}

.t26d7g3rg {
  d: path("M12 18.0031V22");
}

.y-9fctbqs {
  d: path("M19.9997 10.0646C20.0354 14.4827 16.4827 18.0354 12.0646 17.9997C7.64642 17.9641 4.03592 14.3536 4.00027 9.93545C3.96461 5.51731 7.51731 1.96461 11.9354 2.00027C16.3536 2.03592 19.9641 5.64642 19.9997 10.0646Z");
}

</style>
