<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dqwbyi7mt"/><path class="h_3o9c16a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:transmission-fluid" /></template>
<style>
.dqwbyi7mt {
  d: path("m10.36 4.57l.1-.96q.07-.74.82-.74h1.44q.75 0 .82.74l.1.96q.07.74.76 1.03l.43.18q.69.29 1.27-.19l.74-.61q.58-.48 1.11.05l1.02 1.02q.53.53.05 1.11l-.61.74q-.48.58-.19 1.27l.18.43q.29.69 1.03.76l.96.1q.74.07.74.82v1.44q0 .75-.74.82l-.96.1q-.74.07-1.03.76l-.18.43q-.29.69.19 1.27l.61.74q.48.58-.05 1.11l-1.02 1.02q-.53.53-1.11.05l-.74-.61q-.58-.48-1.27-.19l-.43.18q-.69.29-.76 1.03l-.1.96q-.07.74-.82.74h-1.44q-.75 0-.82-.74l-.1-.96q-.07-.74-.76-1.03l-.43-.18q-.69-.29-1.27.19l-.74.61q-.58.48-1.11-.05l-1.02-1.02q-.53-.53-.05-1.11l.61-.74q.48-.58.19-1.27l-.18-.43q-.29-.69-1.03-.76l-.96-.1q-.74-.07-.74-.82v-1.44q0-.75.74-.82l.96-.1q.74-.07 1.03-.76l.18-.43q.29-.69-.19-1.27l-.61-.74q-.48-.58.05-1.11l1.02-1.02q.53-.53 1.11-.05l.74.61q.58.48 1.27.19l.43-.18q.69-.29.76-1.03");
}

.h_3o9c16a {
  d: path("M12 8c1.5 1.75 2.75 3.25 2.75 4.75a2.75 2.75 0 0 1-5.5 0c0-1.5 1.25-3 2.75-4.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
