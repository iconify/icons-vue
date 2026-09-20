<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zuxqwfbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:total-apps-folder-in-folder" /></template>
<style>
.zuxqwfbkj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.138 36.57v3.062h-29.3a2.334 2.334 0 0 1-2.338-2.33V14.696h3.056V36.57zM12.113 10.698a2.334 2.334 0 0 1 2.337-2.33h6.793c.65 0 1.283.202 1.812.579l3.828 2.725c.53.377 1.163.58 1.812.579h11.468a2.334 2.334 0 0 1 2.337 2.33v15.531a2.334 2.334 0 0 1-2.337 2.33H14.45a2.334 2.334 0 0 1-2.337-2.33z");
}

</style>
