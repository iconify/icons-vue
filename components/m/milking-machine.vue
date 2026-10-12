<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g35bqubjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:milking-machine" /></template>
<style>
.g35bqubjv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 3v5m3-5v5m3-5v5m3-5v5m-9.4 0h9.8q.6 0 .27.5l-1.34 2q-.33.5-.93.5h-5.8q-.6 0-.93-.5l-1.34-2q-.33-.5.27-.5m4.9 3v6.5q0 2.25 2.25 2.25h3.9m.6-7.25h5.25q1 0 .91 1l-.57 6.75q-.09 1-1.09 1h-3.75q-1 0-1.09-1l-.57-6.75q-.09-1 .91-1m-.8 2.5h6.85");
}

</style>
