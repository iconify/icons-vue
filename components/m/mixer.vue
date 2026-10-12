<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="puriznbpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mixer" /></template>
<style>
.puriznbpc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 5.5A2.75 2.75 0 0 1 7.5 2.75h9a3.75 3.75 0 0 1 3.75 3.75v1.25a2.5 2.5 0 0 1-2.5 2.5H7.5A2.75 2.75 0 0 1 4.75 7.5ZM8 6.5h4.5m-3 3.75v4.25m5-4.25v4.25m-5 0c-1.6 1-1.6 5.5 0 6.75c1.6-1.25 1.6-5.75 0-6.75m5 0c-1.6 1-1.6 5.5 0 6.75c1.6-1.25 1.6-5.75 0-6.75");
}

</style>
