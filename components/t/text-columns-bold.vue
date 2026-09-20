<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mj8gtub4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:text-columns-bold" /></template>
<style>
.mj8gtub4k {
  fill: currentColor;
  d: path("M120 64a12 12 0 0 1-12 12H40a12 12 0 0 1 0-24h68a12 12 0 0 1 12 12m-12 28H40a12 12 0 0 0 0 24h68a12 12 0 0 0 0-24m0 40H40a12 12 0 0 0 0 24h68a12 12 0 0 0 0-24m0 40H40a12 12 0 0 0 0 24h68a12 12 0 0 0 0-24m40-96h68a12 12 0 0 0 0-24h-68a12 12 0 0 0 0 24m68 16h-68a12 12 0 0 0 0 24h68a12 12 0 0 0 0-24m0 40h-68a12 12 0 0 0 0 24h68a12 12 0 0 0 0-24m0 40h-68a12 12 0 0 0 0 24h68a12 12 0 0 0 0-24");
}

</style>
