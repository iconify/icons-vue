<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rh--lnbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pin" /></template>
<style>
.rh--lnbae {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 3.75h4.5v5.1l3.3 3.45c.6.65.15 1.7-.72 1.7H7.17c-.87 0-1.32-1.05-.72-1.7l3.3-3.45ZM12 14v6.5");
}

</style>
