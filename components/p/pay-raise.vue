<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-d28sbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pay-raise" /></template>
<style>
.f-d28sbkg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16.5H7v5H2.5Zm7.25-4h4.5v9h-4.5Zm7.25-4h4.5v13H17ZM2.5 19H7m2.75-3.5h4.5m-4.5 3h4.5m2.75-7h4.5M17 14.75h4.5M17 18h4.5M3 13.5l11-10m-3.5 0H14V7");
}

</style>
