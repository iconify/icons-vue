<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u7vj4cc9f"/><path class="wepb94fmn"/><path class="lsgjr5bud"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sports-bar" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lsgjr5bud {
  d: path("M9 12.25q3 2.5 6 0");
}

.u7vj4cc9f {
  d: path("M6 7h12a3.5 3.5 0 0 1 3.5 3.5v6A3.5 3.5 0 0 1 18 20H6a3.5 3.5 0 0 1-3.5-3.5v-6A3.5 3.5 0 0 1 6 7m6 0L8.5 3M12 7l3.5-4");
}

.wepb94fmn {
  d: path("M8.75 13.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

</style>
