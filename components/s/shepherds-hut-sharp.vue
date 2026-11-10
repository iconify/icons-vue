<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nek7a308i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shepherds-hut-sharp" /></template>
<style>
.nek7a308i {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 4C20.209 4 22 5.79 22 8V18H18M18 4V8M18 4H13M18 18V16M18 18V20M18 8H13M18 8V12M13 4V8M13 4H7M18 16V12M18 16H13M18 20H13M18 20V23M13 8V12M18 12H13M7 4H2V18H7M7 4V1M7 18C5.895 18 5 18.9 5 20C5 21.1 5.895 22 7 22C8.105 22 9 21.1 9 20C9 18.9 8.105 18 7 18ZM7 18H13M13 18V16M13 18V20M13 16V12M13 20V23M2 8H6V12H2");
}

</style>
