<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i4wove82l"/><path class="ks1aw0btu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:statement-certified" /></template>
<style>
.i4wove82l {
  d: path("M8 2.5h9.5q.098 0 .196.01q.098.009.194.028q.097.02.191.048q.094.029.184.066q.091.038.178.084q.086.046.168.101t.158.117t.145.132t.132.145t.117.158t.101.168q.046.087.084.178q.037.09.066.184q.028.094.048.191q.019.096.028.194t.01.196v7.072");
}

.ks1aw0btu {
  d: path("M13.4 21.5H4.5V5H17v6.2M7.5 9H14m-6.5 3.5H14M7.5 16H10m8-2l.695.61l.921-.085l.204.902l.795.473l-.365.85l.365.85l-.795.473l-.204.902l-.921-.085l-.695.61l-.695-.61l-.921.085l-.204-.902l-.795-.473l.365-.85l-.365-.85l.795-.473l.204-.902l.921.085Zm-1.25 5.25l-.5 2.5m3-2.5l.5 2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
