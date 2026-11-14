<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs2h9ubra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:service-ivr-menu" /></template>
<style>
.vs2h9ubra {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.735 16.723C7.078 15.47 2.5 10.146 2.5 4.25c0-1 .75-1.75 1.75-1.75h2.5c.75 0 1 .5 1.25 1L8.75 6q0 1.125-.75 1.5l-1.25 1c1 2 2 3.25 4.25 4.25l.75-1.25q.75-.75 1.5-.75l2.75.75c.468 0 .936.438.994 1.109M15.25 15.25h.01m2.74 0h.01m2.74 0h.01M15.25 18h.01M18 18h.01m2.74 0h.01m-5.51 2.75h.01m2.74 0h.01m2.74 0h.01");
}

</style>
