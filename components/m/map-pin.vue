<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmpw9tbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:map-pin" /></template>
<style>
.rmpw9tbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.962848 15.333333L12 22L6.037152 15.333333C4.725272 13.866607 4 11.96782 4 10C4 5.581722 7.581722 2 12 2C16.418278 2 20 5.581722 20 10C20 11.96782 19.274728 13.866607 17.962848 15.333333ZM15 10C15 11.6569 13.6569 13 12 13C10.3431 13 9 11.6569 9 10C9 8.3431 10.3431 7 12 7C13.6569 7 15 8.3431 15 10Z");
}

</style>
