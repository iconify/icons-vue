<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nuojty7yl"/><path class="r_rndobuu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:resource-delete" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nuojty7yl {
  d: path("m13.02 19.927l-1.199.637q-.19.101-.398.153t-.423.052t-.423-.052t-.398-.153l-6.25-3.32q-.105-.056-.201-.125t-.182-.151q-.086-.081-.161-.174q-.074-.092-.135-.194t-.108-.211t-.078-.223t-.048-.232T3 15.698V9.302q0-.119.016-.236q.016-.118.048-.232q.031-.114.078-.223T3.25 8.4t.135-.194q.075-.093.161-.174q.086-.082.182-.151t.201-.125l6.25-3.32q.19-.101.398-.153T11 4.231t.423.052t.398.153l6.25 3.32q.105.056.201.125t.182.151t.161.174q.074.092.135.194t.108.211t.078.223q.032.114.048.232q.016.117.016.236v5.919");
}

.r_rndobuu {
  d: path("m3 8.25l8 4.25l8-4.25m-8 4.25V21m4-3h6");
}

</style>
