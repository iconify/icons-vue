<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe8gy8bcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:marina" /></template>
<style>
.xe8gy8bcy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 5.1v5.05q0 .6-.6.6H3.35q-.6 0-.26-.5L6.66 5q.34-.5.34.1m-4.25 8.15h8.5l-1 2.6a1.25 1.25 0 0 1-1.17.8H4.92a1.25 1.25 0 0 1-1.17-.8ZM17 5.1v5.05q0 .6.6.6h3.05q.6 0 .26-.5L17.34 5q-.34-.5-.34.1m-4.25 8.15h8.5l-1 2.6a1.25 1.25 0 0 1-1.17.8h-4.16a1.25 1.25 0 0 1-1.17-.8Zm-10 6h18.5m-9.25 0v2M7 11v2.25M17 11v2.25");
}

</style>
