<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="x-rnjk3fz"/><path class="p39idcbfe"/><path class="arc04wbve"/><path class="dpk712b_i"/><path class="c3t75_bqf"/><path class="op1ybnlot"/><path class="zvobeac5y"/><path class="si_mtzbvj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:safe-square-broken" /></template>
<style>
.arc04wbve {
  d: path("M12.5 9.40135C12.9413 9.14609 13.4536 9 14 9C15.6569 9 17 10.3431 17 12C17 13.6569 15.6569 15 14 15C12.3431 15 11 13.6569 11 12C11 11.4536 11.1461 10.9413 11.4013 10.5");
}

.c3t75_bqf {
  d: path("M10 16L11.5 14.5");
}

.dpk712b_i {
  d: path("M16.5 9.5L18 8");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.op1ybnlot {
  d: path("M11.5 9.5L10 8");
}

.p39idcbfe {
  d: path("M14 15C12.3431 15 11 13.6569 11 12C11 10.3431 12.3431 9 14 9C15.6569 9 17 10.3431 17 12C17 13.6569 15.6569 15 14 15Z");
}

.si_mtzbvj {
  d: path("M22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C21.5093 4.43821 21.8356 5.80655 21.9449 8");
}

.x-rnjk3fz {
  d: path("M6 7L6 8M6 12L6 17");
}

.zvobeac5y {
  d: path("M18 16L16.5 14.5");
}

</style>
