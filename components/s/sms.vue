<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="rmm1voz9v"/><path class="b0t3z17sp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sms" /></template>
<style>
.b0t3z17sp {
  d: path("M9.25 7.25h5.5a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1H11.5l-2 1.5v-1.5h-.25a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1m1.5 10.5h2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rmm1voz9v {
  width: 12.5px;
  height: 18.5px;
  x: 5.75px;
  y: 2.75px;
  rx: 2.5px;
}

</style>
