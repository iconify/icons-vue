<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgozlgb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:phone-hangup" /></template>
<style>
.hgozlgb8u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8.5c3.6 0 6.9 1.2 8.65 3.05c.55.6.55 1.5 0 2.1L19.1 15.3a1 1 0 0 1-1.2.2l-2.6-1.3a1 1 0 0 1-.55-.9v-1.9A12 12 0 0 0 12 11a12 12 0 0 0-2.75.4v1.9a1 1 0 0 1-.55.9l-2.6 1.3a1 1 0 0 1-1.2-.2l-1.55-1.65c-.55-.6-.55-1.5 0-2.1C5.1 9.7 8.4 8.5 12 8.5m0 5.5v5.5m-2.25-2.25L12 19.5l2.25-2.25");
}

</style>
