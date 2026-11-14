<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t9sxlta2n"/><path class="u9_i14azq"/><path class="ro5dg0wjp"/><path class="irnup5byk"/><path class="qc1rb6b7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:yen-broken" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.irnup5byk {
  d: path("M9.25 12H14.75");
}

.qc1rb6b7c {
  d: path("M9.25 14.5H14.75");
}

.ro5dg0wjp {
  d: path("M12 12V17");
}

.t9sxlta2n {
  d: path("M6.99975 3.33969C11.3457 0.830591 16.8783 1.93109 19.9332 5.91239C22.9882 9.89369 22.6192 15.5226 19.0708 19.0711C15.5223 22.6195 9.89345 22.9885 5.91215 19.9335C1.93085 16.8786 0.830347 11.346 3.33945 6.99999");
}

.u9_i14azq {
  d: path("M8.5 7L12 12L15.5 7");
}

</style>
