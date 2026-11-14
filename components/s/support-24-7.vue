<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rtmwcpr8e"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:support-24-7" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rtmwcpr8e {
  d: path("M4.75 11v-.5a7.25 7.25 0 0 1 14.5 0v.5m-14.5 0zA2.25 2.25 0 0 1 7 13.25v2.5A2.25 2.25 0 0 1 4.75 18a2.25 2.25 0 0 1-2.25-2.25v-2.5A2.25 2.25 0 0 1 4.75 11m12.656.96q.078-.11.168-.211t.192-.19t.213-.166t.232-.139t.246-.11q.127-.047.258-.079q.131-.033.266-.049q.134-.016.269-.016q.105 0 .209.01q.104.009.207.029q.103.019.204.048t.198.067t.191.085t.183.103t.172.119t.16.134t.147.149q.071.078.133.162t.117.173t.101.184q.046.094.083.192t.065.199t.046.204t.026.207M4.75 18a3 3 0 0 0 3 3H10m4.75-3a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

</style>
