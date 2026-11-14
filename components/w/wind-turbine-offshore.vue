<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0or59bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wind-turbine-offshore" /></template>
<style>
.k0or59bzc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8.5v-6m0 6l5.5 3.25M12 8.5l-5.5 3.25M12 8.5v12m-9.5 0q2.375-2 4.75 0t4.75 0t4.75 0t4.75 0");
}

</style>
