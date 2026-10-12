<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbgr5_b6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ship-sharp" /></template>
<style>
.bbgr5_b6u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 12h16.5l-1.75 4.35l-.416 1.14l-1.214.01H7.13l-1.214-.01l-.416-1.14Zm4 0V7h8.5v5M12 7V3.75M3 21c1.5 0 1.5-1 3-1s1.5 1 3 1s1.5-1 3-1s1.5 1 3 1s1.5-1 3-1s1.5 1 3 1");
}

</style>
