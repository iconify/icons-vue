<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kdgrazjnx"/><path class="jhxtg0dcw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:news-podcast" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jhxtg0dcw {
  d: path("M3 10q0 .153.008.307q.007.153.022.306q.015.152.038.304q.022.152.052.302q.03.151.067.3q.038.148.082.295t.096.292t.111.286q.058.142.124.28t.138.274t.151.267t.164.259q.086.128.177.251t.189.242t.2.232t.212.222q.108.109.222.212q.113.103.232.2t.242.189q.123.091.251.177q.127.085.259.164q.131.079.267.151q.135.072.274.138q.138.066.28.124q.142.059.286.111q.145.051.292.096q.147.044.295.082q.149.037.3.067q.15.03.302.052q.152.023.304.038q.153.015.306.022q.154.008.307.008q.788 0 1.551-.195q.763-.196 1.453-.574m2.933-3.527q.313-.952.313-1.954m-6.25 6.25v4.25M6 20.5h6.3m4.45-6h3.5A1.75 1.75 0 0 1 22 16.25v3.5a1.75 1.75 0 0 1-1.75 1.75h-3.5A1.75 1.75 0 0 1 15 19.75v-3.5a1.75 1.75 0 0 1 1.75-1.75");
}

.kdgrazjnx {
  d: path("M9.25 2.5za3.25 3.25 0 0 1 3.25 3.25v4A3.25 3.25 0 0 1 9.25 13A3.25 3.25 0 0 1 6 9.75v-4A3.25 3.25 0 0 1 9.25 2.5");
}

</style>
