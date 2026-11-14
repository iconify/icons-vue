<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ap-z57bve"/><path class="sp_4vy3gf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ticket-accessible" /></template>
<style>
.ap-z57bve {
  d: path("M2.5 4h19v5.5a2.5 2.5 0 0 0 0 5V20h-19v-5.5a2.5 2.5 0 0 0 0-5Zm10 3h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sp_4vy3gf {
  d: path("M12.5 9.5v4h3.25L17 17m-3.046-1.479a3 3 0 1 1-3.98-3.34");
}

</style>
