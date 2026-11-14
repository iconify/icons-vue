<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1uyq679f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tax-bracket" /></template>
<style>
.j1uyq679f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.7 15.5H3v-4h4.75V7.25h4.5V3H17v10.1m-9.25-1.6v4m4.5-8.25v8.25m2.5 5.75l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

</style>
