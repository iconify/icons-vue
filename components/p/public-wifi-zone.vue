<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_wlrxbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:public-wifi-zone" /></template>
<style>
.m_wlrxbsp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 10h.01M9.879 7.879a3 3 0 0 1 4.242 0M7.757 5.757a6 6 0 0 1 8.486 0M4 13.5h16M2.5 17h19m-16-3.5V21m13-7.5V21");
}

</style>
