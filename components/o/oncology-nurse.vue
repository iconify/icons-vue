<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tipo4kbqr"/><path class="nkanfobft"/><path class="u_22_ofci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:oncology-nurse" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nkanfobft {
  fill: currentColor;
  d: path("m6.75 4.75l1-2.5h5.5l1 2.5q-3.75-1.125-7.5 0");
}

.tipo4kbqr {
  d: path("M13.272 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c1.074 0 2.085.144 2.995.411M6.541 7.568q.025.177.066.351q.041.173.097.343q.057.17.128.333q.071.164.157.321q.085.157.185.305q.099.149.211.288t.236.268t.259.246t.28.221q.145.105.298.196q.154.091.315.168t.329.14q.167.062.339.109q.173.048.349.079q.175.032.353.048T10.5 11t.36-.016q.179-.016.357-.049q.177-.032.351-.08t.343-.112q.168-.064.331-.142q.162-.079.316-.171q.155-.093.301-.199q.145-.107.281-.226q.135-.119.26-.249q.124-.131.236-.273q.112-.141.21-.292q.099-.151.184-.31t.155-.325t.125-.338t.094-.348t.063-.354");
}

.u_22_ofci {
  d: path("m15.75 21.75l3.75-5.5c.75-1.25 0-2.5-1.5-2.5s-2.25 1.25-1.5 2.5l3.75 5.5");
}

</style>
