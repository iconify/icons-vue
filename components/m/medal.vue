<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bds_koqxg"/><circle class="ydy0opbpr"/><path class="a-c8zdkkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:medal" /></template>
<style>
.a-c8zdkkl {
  d: path("m12.16 13.37l.42 1q.15.37.55.4l1.09.1q.4.03.09.29l-.82.71q-.3.27-.21.66l.25 1.06q.09.38-.26.18l-.93-.56q-.34-.21-.68 0l-.93.56q-.35.2-.26-.18l.25-1.06q.09-.39-.21-.66l-.82-.71q-.31-.26.09-.29l1.09-.1q.4-.03.55-.4l.42-1q.16-.37.32 0");
}

.bds_koqxg {
  d: path("m6.75 2.75l3.5 7m7-7l-3.5 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ydy0opbpr {
  cx: 12px;
  cy: 15.5px;
  r: 5.75px;
}

</style>
