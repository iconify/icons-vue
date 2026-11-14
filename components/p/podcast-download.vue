<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m1sr9n5fp"/><path class="p98qncc9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:podcast-download" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m1sr9n5fp {
  d: path("M10.5 2.5zA3.5 3.5 0 0 1 14 6v4a3.5 3.5 0 0 1-3.5 3.5A3.5 3.5 0 0 1 7 10V6a3.5 3.5 0 0 1 3.5-3.5");
}

.p98qncc9m {
  d: path("M4.5 10.5q0 .147.007.294q.007.148.022.294q.014.147.036.292q.022.146.05.291q.029.144.065.287t.078.284t.093.279q.049.139.106.275t.119.269t.132.263t.146.257q.075.126.157.248q.082.123.17.241q.087.119.181.232q.093.114.192.223t.203.214q.105.104.214.203t.223.192t.232.181t.241.17t.248.157q.127.076.257.146t.263.132t.269.119t.275.106t.279.093q.141.042.284.078t.287.065q.145.028.291.05q.145.022.292.036q.146.015.294.022q.147.007.294.007q.344 0 .685-.039q.342-.04.677-.118q.334-.078.658-.193q.324-.116.632-.268q.309-.152.598-.338q.288-.186.554-.404t.505-.465t.449-.52m.936-1.764q.306-.921.306-1.891m-6 6v4m-3 0H13m5-6v7m-3-3l3 3l3-3");
}

</style>
