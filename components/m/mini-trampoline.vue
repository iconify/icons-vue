<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hiqabfbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mini-trampoline" /></template>
<style>
.hiqabfbzs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 13.5a9 3.5 0 1 0 18 0a9 3.5 0 1 0-18 0M6 16l-.5 4.5M18 16l.5 4.5M12 7.25V2.5M9.5 5L12 2.5L14.5 5");
}

</style>
