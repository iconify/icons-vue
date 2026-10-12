<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6eycybhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mortar-pestle-stone" /></template>
<style>
.v6eycybhi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.01 10.89l3.98-6.78q.51-.86 1.33-.29l.86.61q.82.57.31 1.43l-2.98 5.03q-.51.86-1.51.86h-1.5q-1 0-.49-.86M3 11.75h18c0 4-3.75 7-9 7s-9-3-9-7m5.5 9.5h7");
}

</style>
