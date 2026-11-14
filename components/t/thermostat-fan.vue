<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="goiz_9b_e"/><path class="qggcqlxou"/><path class="l5rrcht1u"/><path class="ub2kwibij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:thermostat-fan" /></template>
<style>
.goiz_9b_e {
  d: path("M6.551 19.782a9.5 9.5 0 1 1 10.898 0M12 2.5v2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l5rrcht1u {
  d: path("M12.65 12.375za1.25 1.25 0 0 1-1.708.458L8.56 11.458a1.25 1.25 0 0 1-.457-1.708a1.25 1.25 0 0 1 1.707-.458l2.382 1.375a1.25 1.25 0 0 1 .458 1.708");
}

.qggcqlxou {
  d: path("M12 11.25za1.25 1.25 0 0 1 1.25 1.25v2.75A1.25 1.25 0 0 1 12 16.5a1.25 1.25 0 0 1-1.25-1.25V12.5A1.25 1.25 0 0 1 12 11.25");
}

.ub2kwibij {
  d: path("M11.35 12.375za1.25 1.25 0 0 1 .458-1.708l2.382-1.375a1.25 1.25 0 0 1 1.707.458a1.25 1.25 0 0 1-.457 1.708l-2.382 1.375a1.25 1.25 0 0 1-1.708-.458");
}

</style>
