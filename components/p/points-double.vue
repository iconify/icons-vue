<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc_z9-igr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:points-double" /></template>
<style>
.zc_z9-igr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.307 16.419L11 16.25l-5.143 2.829l1.101-5.766l-4.28-4.017l5.824-.734L11 3.25l2.498 5.312l5.824.734l-4.28 4.017l.242 1.267M14.25 17.5l2.5 2.5m0-2.5l-2.5 2.5m4-4c.25-.75.75-1.25 1.5-1.25q1.5 0 1.5 1.5c0 1.25-3 2.25-3 5h3.25");
}

</style>
