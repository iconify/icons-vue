<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxssmhbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:stationary-boundary" /></template>
<style>
.mxssmhbeh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.25 3.25h3.5q1.036 0 1.768.732t.732 1.768t-.732 1.768q-.129.129-.268.235v3.244q2.09.339 3.789 1.143Q22.25 13.661 22.25 16t-3.211 3.86Q16.104 21.25 12 21.25t-7.039-1.39Q1.75 18.339 1.75 16t3.211-3.86q1.699-.804 3.789-1.143V7.753q-.139-.106-.268-.235q-.732-.732-.732-1.768q0-2.5 2.5-2.5m3.5 7.567V8.25h-3.5v2.567q.847-.067 1.75-.067t1.75.067");
}

</style>
