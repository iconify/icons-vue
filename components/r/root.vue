<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t92bzbb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:root" /></template>
<style>
.t92bzbb0z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 11h18.5M12 8.5v9c0 1.5-.75 2.75-2 3.75m2-7.75c-1.5 0-3 .75-4.25 2.25c-.75.75-1.25 2-1.25 3.25m5.5-4.25c1.75 0 3.25 1 4.25 2.5c.5.75.75 1.75.75 2.75M12 8.5c-.25-2.75-2-4.25-5-4.25C7.25 7 9 8.5 12 8.5m0 0c.25-2.75 2-4.25 5-4.25C16.75 7 15 8.5 12 8.5");
}

</style>
