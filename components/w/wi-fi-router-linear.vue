<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tbc2yaclk"/><path class="vjx83pbji"/><path class="pxumu3byy"/><path class="x3iyvacvu"/><path class="dbv406bra"/><path class="qai50qlum"/><path class="sgm0_f_wv"/><path class="o7pb9dbnw"/><path class="nhpgumbwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wi-fi-router-linear" /></template>
<style>
.dbv406bra {
  d: path("M17.1673 5.39702C16.3414 3.40286 14.3763 2 12.0836 2C9.79092 2 7.82586 3.40286 7 5.39702");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nhpgumbwq {
  stroke-linejoin: round;
  d: path("M6 15H6.0001");
}

.o7pb9dbnw {
  stroke-linejoin: round;
  d: path("M9 15H9.0001");
}

.pxumu3byy {
  d: path("M17 11L21 4");
}

.qai50qlum {
  d: path("M14.9646 6.65811C14.6007 5.41107 13.4489 4.5 12.0844 4.5C10.7198 4.5 9.568 5.41107 9.2041 6.65811");
}

.sgm0_f_wv {
  stroke-linejoin: round;
  d: path("M12 7H12.0001");
}

.tbc2yaclk {
  d: path("M6 19H18C19.8856 19 20.8284 19 21.4142 18.4142C22 17.8284 22 16.8856 22 15C22 13.1144 22 12.1716 21.4142 11.5858C20.8284 11 19.8856 11 18 11H6C4.11438 11 3.17157 11 2.58579 11.5858C2 12.1716 2 13.1144 2 15C2 16.8856 2 17.8284 2.58579 18.4142C3.17157 19 4.11438 19 6 19Z");
}

.vjx83pbji {
  d: path("M7 11L3 4");
}

.x3iyvacvu {
  d: path("M14 15L18 15");
}

</style>
