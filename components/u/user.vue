<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqdttgbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:user" /></template>
<style>
.dqdttgbrq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.25 7.5q0-1.968 1.391-3.359T12 2.75t3.359 1.391T16.75 7.5t-1.391 3.359T12 12.25t-3.359-1.391T7.25 7.5m-1.315 7.888Q3.25 17.17 3.25 20q0 1.75 1.75 1.75h14q1.75 0 1.75-1.75q0-2.83-2.685-4.612Q15.598 13.75 12 13.75t-6.065 1.638");
}

</style>
