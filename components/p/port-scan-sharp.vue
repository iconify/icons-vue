<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hu0_oh4zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:port-scan-sharp" /></template>
<style>
.hu0_oh4zl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 9.75H20.5v6.75h-4v4.75h-9V16.5h-4V9.75zM8 12.25v2m2.67-2v2m2.66-2v2m2.67-2v2M12 6.5V2.75m-5.25 4.5L5 4.75m12.25 2.5L19 4.75");
}

</style>
