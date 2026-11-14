<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shw7r9b_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pyjamas" /></template>
<style>
.shw7r9b_e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.5 3l-3 .75c-1 .25-1.75 1-2 2l-2 10h3.25l2-5.75v11h8.5V10l2 5.75h3.25l-2-10c-.25-1-1-1.75-2-2l-3-.75L12 7.5Zm2.5 8h.01M12 14.5h.01M12 18h.01");
}

</style>
