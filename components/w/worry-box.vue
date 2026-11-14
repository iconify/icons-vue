<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avwy0kbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:worry-box" /></template>
<style>
.avwy0kbpx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 3.5h13.75A2.625 2.625 0 0 1 21.5 6.125v.75A2.625 2.625 0 0 1 18.875 9.5H5.125A2.625 2.625 0 0 1 2.5 6.875v-.75A2.625 2.625 0 0 1 5.125 3.5M4 9.5v9q0 .098.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145q.069.07.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028T6 20.5h4.772M20 12.257V9.5m-11-3h6m.5 14a2.5 2.5 0 0 1 0-5a3 3 0 0 1 5 1a2.25 2.25 0 0 1-1 4Z");
}

</style>
