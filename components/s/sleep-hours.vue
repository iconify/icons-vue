<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awnvqjbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sleep-hours" /></template>
<style>
.awnvqjbik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3v16m0-9.5h16q.098 0 .196.01q.098.009.194.028q.097.02.191.048q.094.029.184.066q.091.038.178.084q.086.046.168.101t.158.117t.145.132t.132.145t.117.158t.101.168q.046.087.084.178q.037.09.066.184q.028.094.048.191q.019.096.028.194t.01.196v.872M12.828 15.5H3m5-10h1.5a2 2 0 0 1 2 2a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2a2 2 0 0 1 2-2m11.5 9.25a3.5 3.5 0 1 0 2.25 4.75a3 3 0 0 1-2.25-4.75");
}

</style>
