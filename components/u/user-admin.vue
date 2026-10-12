<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="rknchmb5r"/><path class="g-idrkbpc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-admin" /></template>
<style>
.g-idrkbpc {
  d: path("M4 20.25h11a.75.75 0 0 0 .75-.75c0-3-2.8-5.25-6.25-5.25S3.25 16.5 3.25 19.5a.75.75 0 0 0 .75.75M16.17 8.61l.96 2.03q.17.36.29-.02l1.06-3.24q.12-.38.25 0l1.09 3.24q.13.38.3.02l.96-2.03q.17-.36.17.04v4.45q0 .4-.4.4H16.4q-.4 0-.4-.4V8.65q0-.4.17-.04");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rknchmb5r {
  cx: 9.5px;
  cy: 7.75px;
  r: 3.75px;
}

</style>
