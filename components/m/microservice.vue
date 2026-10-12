<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajgg5431a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:microservice" /></template>
<style>
.ajgg5431a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.37 5l1.51.88q.87.5.87 1.5v1.75q0 1-.87 1.5l-1.51.87q-.87.5-1.74 0l-1.51-.87q-.87-.5-.87-1.5V7.38q0-1 .87-1.5L6.63 5q.87-.5 1.74 0m9 0l1.51.88q.87.5.87 1.5v1.75q0 1-.87 1.5l-1.51.87q-.87.5-1.74 0l-1.51-.87q-.87-.5-.87-1.5V7.38q0-1 .87-1.5L15.63 5q.87-.5 1.74 0m-4.5 7.75l1.51.88q.87.5.87 1.5v1.75q0 1-.87 1.5l-1.51.87q-.87.5-1.74 0l-1.51-.87q-.87-.5-.87-1.5v-1.75q0-1 .87-1.5l1.51-.88q.87-.5 1.74 0");
}

</style>
