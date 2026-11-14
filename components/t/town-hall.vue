<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyo2pac_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:town-hall" /></template>
<style>
.wyo2pac_o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 2.5h4a1 1 0 0 1 1 1v7a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1v-7a1 1 0 0 1 1-1Zm2 9v9.75m-4 0h4.2M7 7h6m1.25 9.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM13 21.75c0-1.5 1.25-2.5 3-2.5s3 1 3 2.5m-.25-7.799a1.5 1.5 0 1 1 .237 2.709M20 18.5c1 .25 1.75 1.25 1.75 3");
}

</style>
