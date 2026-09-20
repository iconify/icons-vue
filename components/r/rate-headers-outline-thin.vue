<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="abnm6smsv"/><path class="mfc7nxp-y"/><path class="wh3w9jgzq"/><path class="hr6wkp7wg"/><path class="lhg9en3sp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rate-headers-outline-thin" /></template>
<style>
.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hr6wkp7wg {
  d: path("M12 9.5V16");
}

.lhg9en3sp {
  d: path("M15 13v3");
}

.mfc7nxp-y {
  d: path("M9 7h6");
}

.wh3w9jgzq {
  d: path("M9 11.5V16");
}

</style>
