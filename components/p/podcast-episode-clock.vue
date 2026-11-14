<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eip78p0re"/><path class="kojnx9y2b"/><path class="k-f1vzp8y"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:podcast-episode-clock" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.eip78p0re {
  d: path("M13.043 21.5H3.5v-19h10l3 3v6.657");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k-f1vzp8y {
  d: path("M7.348 15.652q-.13-.13-.247-.273q-.117-.142-.219-.295q-.103-.153-.189-.316q-.087-.162-.158-.333q-.07-.17-.124-.346t-.089-.357t-.054-.364T6.25 13q0-.184.018-.367t.054-.364t.09-.357t.124-.347t.157-.332q.087-.163.189-.316t.219-.295q.117-.143.247-.273q.131-.13.273-.247t.296-.219t.315-.19q.163-.086.333-.157q.17-.07.346-.124q.177-.053.357-.089q.181-.036.364-.054q.184-.018.368-.018t.368.018t.364.054t.357.089t.346.124t.333.157t.315.19q.153.102.296.219q.142.117.273.247q.166.166.31.352t.264.387t.213.418t.16.441t.103.457q.038.232.046.467q.008.234-.013.468q-.022.234-.072.464M10 14v4.75m4.75-.75a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

.kojnx9y2b {
  d: path("M13.5 2.5v3h3M9 13a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>
