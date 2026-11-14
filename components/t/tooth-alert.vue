<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dskqn_dqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tooth-alert" /></template>
<style>
.dskqn_dqb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.478 13.619l.022-.119c.5-1.5 1.5-3 2-5.5s0-4.5-2-4.5c-1.5 0-2.5.75-4.5.75S8 3.5 6.5 3.5c-2 0-2.5 2-2 4.5s1.5 4 2 5.5l1 5.5c.25 1 1.25 1 1.5 0l.75-5h2.5l.75 5c.25 1 1.25 1 1.5 0l.746-4.102M18 14.75v3.5M18 21h.01");
}

</style>
