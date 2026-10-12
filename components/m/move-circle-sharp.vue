<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmjia0bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:move-circle-sharp" /></template>
<style>
.vmjia0bep {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.75v16.5M3.75 12h16.5m-11-5.5L12 3.75l2.75 2.75m-5.5 11L12 20.25l2.75-2.75M6.5 9.25L3.75 12l2.75 2.75m11-5.5L20.25 12l-2.75 2.75");
}

</style>
