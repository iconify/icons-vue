<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-987ac0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:software-uninstall" /></template>
<style>
.f-987ac0b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 20.25h-6a2.5 2.5 0 0 1-2.5-2.5V6.25a2.5 2.5 0 0 1 2.5-2.5h13.5a2.5 2.5 0 0 1 2.5 2.5v5.5m-18.5-3.5h18.5m-15 3.5h4.5m4.5 3.5l4.5 4.5m0-4.5l-4.5 4.5");
}

</style>
