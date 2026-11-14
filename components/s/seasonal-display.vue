<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_bhhpm5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:seasonal-display" /></template>
<style>
.s_bhhpm5f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 16h13.5a1.75 1.75 0 0 1 1.75 1.75v2a1.75 1.75 0 0 1-1.75 1.75H5.25a1.75 1.75 0 0 1-1.75-1.75v-2A1.75 1.75 0 0 1 5.25 16M13.2 4.1l2.625 3.5a.563.563 0 0 1-.45.9a.611.611 0 0 0-.512.943l1.131 1.74a1.5 1.5 0 0 1-1.258 2.317H9.264a1.5 1.5 0 0 1-1.258-2.317l1.131-1.74a.611.611 0 0 0-.512-.943a.563.563 0 0 1-.45-.9L10.8 4.1a1.5 1.5 0 0 1 2.4 0M12 13.5V16m-5.5 2.75h11");
}

</style>
