<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uh84k3rvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:message-text-sharp" /></template>
<style>
.uh84k3rvu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.25v-2.5h18.5v14H12.5L8 20.85l-1.25 1v-4.1h-4v-2.5Zm4.5 2.5h9.5m-9.5 4h6");
}

</style>
