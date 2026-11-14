<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anpnfr14e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:missed-collection" /></template>
<style>
.anpnfr14e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 7.5l1-3H17l1 3Zm1.5 0l1.25 13h6.04m3.739-8.103L16.5 7.5M15 15l6 6m0-6l-6 6");
}

</style>
