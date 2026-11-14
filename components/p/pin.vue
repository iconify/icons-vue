<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwdqosbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin" /></template>
<style>
.lwdqosbfy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 3.5h1.5a1.75 1.75 0 0 1 1.75 1.75v2.74a1.75 1.75 0 0 0 .274.94l1.514 2.38A1.75 1.75 0 0 1 14.812 14H9.188a1.75 1.75 0 0 1-1.476-2.69l1.514-2.38a1.75 1.75 0 0 0 .274-.94V5.25a1.75 1.75 0 0 1 1.75-1.75M12 14v7");
}

</style>
