<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oxpnpp0rq"/><path class="kc1yf3bro"/><path class="xlc4mgbbf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vault-room" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kc1yf3bro {
  d: path("M6.5 11a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

.oxpnpp0rq {
  d: path("M4.25 3h15.5a1.75 1.75 0 0 1 1.75 1.75v12.5A1.75 1.75 0 0 1 19.75 19H4.25a1.75 1.75 0 0 1-1.75-1.75V4.75A1.75 1.75 0 0 1 4.25 3M2.5 21.5h19");
}

.xlc4mgbbf {
  d: path("M10.5 11a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M12 9.5v-4m1.25 6.25l3.5 2m-6-2l-3.5 2");
}

</style>
