<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mki-ofb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:water-tower-sharp" /></template>
<style>
.mki-ofb8o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.75h14.5v8.5H4.75zm0 4.25h14.5m-12.5 4v10.25M17.25 11v10.25M6.75 17h3.5m3.5 0h3.5M12 11.25v10");
}

</style>
