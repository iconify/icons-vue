<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cigy526xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:map-tilt" /></template>
<style>
.cigy526xb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.297 5.681l2.28-.912a1.75 1.75 0 0 1 1.339.017l2.168.928a1.75 1.75 0 0 0 1.339.017l1.295-.518a1.75 1.75 0 0 1 2.327 1.128l2.963 9.999a1.75 1.75 0 0 1-1.163 2.169l-4.309 1.326a1.75 1.75 0 0 1-1.068-.012l-4.936-1.646a1.75 1.75 0 0 0-1.068-.012l-2.88.886a1.75 1.75 0 0 1-2.198-2.153L6.264 6.825a1.75 1.75 0 0 1 1.033-1.144M10.25 4.5L9 18m4.75-12L15 20");
}

</style>
