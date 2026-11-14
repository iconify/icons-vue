<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op3nmqn4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:street-team" /></template>
<style>
.op3nmqn4l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.25 16.887V20.5H3.5c-.6 0-1-.4-1-1c0-3 2.9-5 6.5-5c1.25 0 2.35.25 3.25.75v1.437M5.5 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M16 4.5q.158 0 .315.014t.312.042q.155.029.307.071t.299.097t.29.124t.277.15t.262.173q.128.093.246.197q.119.104.228.218q.108.114.206.238t.185.255q.086.132.161.271q.074.139.136.284q.061.145.109.295t.083.304t.055.31q.033.248.03.498t-.042.498q-.038.247-.111.486t-.18.465q-.107.227-.244.436q-.138.208-.304.396q-.166.187-.356.348q-.191.162-.403.295M18 21.5c-1.75-1.75-3-3.25-3-4.75a3 3 0 0 1 6 0c0 1.5-1.25 3-3 4.75");
}

</style>
