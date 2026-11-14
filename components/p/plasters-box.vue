<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tm4cs6ehg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:plasters-box" /></template>
<style>
.tm4cs6ehg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.586 4.929l8.485 8.485a4 4 0 0 1 0 5.657a4 4 0 0 1-5.657 0l-8.485-8.485a4 4 0 0 1 0-5.657a4 4 0 0 1 5.657 0m2.121 2.121L7.05 12.707m9.9-1.414l-5.657 5.657M12 12h.01");
}

</style>
