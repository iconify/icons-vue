<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p928xnhro"/><path class="nhxb0gb3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:public-hearing" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nhxb0gb3y {
  d: path("M2.5 9.5q0 .141.007.282t.021.282t.034.28t.048.278q.028.138.062.275q.035.137.076.272t.088.268t.102.263q.054.131.114.258q.06.128.127.253q.066.124.139.245t.151.239q.078.117.163.23q.084.114.173.223q.09.109.185.213q.094.105.194.205t.205.194q.104.095.213.185q.109.089.223.173q.113.085.23.163t.239.151q.121.073.245.139q.125.067.253.127q.127.06.258.114q.13.054.263.102t.268.088t.272.076q.137.034.275.062q.139.027.278.048q.14.02.28.034t.282.021t.282.007q.403 0 .802-.056q.4-.057.787-.168t.756-.276t.709-.378m2.168-2.465q.261-.566.394-1.175Q14 10.123 14 9.5m-5.75 5.75v5.25M5 20.5h6.5m3.5-6h5.5a1 1 0 0 1 1 1v3.25a1 1 0 0 1-1 1H18l-2 1.75v-1.75h-1a1 1 0 0 1-1-1V15.5a1 1 0 0 1 1-1");
}

.p928xnhro {
  d: path("M8.25 2.5za3 3 0 0 1 3 3v4a3 3 0 0 1-3 3a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3");
}

</style>
