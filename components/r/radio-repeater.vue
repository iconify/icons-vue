<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve9-9pjbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:radio-repeater" /></template>
<style>
.ve9-9pjbg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 21h12M8 21l4-11l4 11M12 7h.01M8.752 8.875a3.75 3.75 0 0 1 0-3.75m6.496 0a3.75 3.75 0 0 1 0 3.75M5.505 10.75a7.5 7.5 0 0 1 0-7.5m12.99 0a7.5 7.5 0 0 1 0 7.5");
}

</style>
