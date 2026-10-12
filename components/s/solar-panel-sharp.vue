<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hr_mnxbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:solar-panel-sharp" /></template>
<style>
.hr_mnxbgc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3.25h13l.2.98l1.85 9.04l.2.98H2.75l.2-.98L4.8 4.23l.2-.98zm6 0v11m-8.05-5.5h16.1M12 14.25v7m-3.5 0h7");
}

</style>
