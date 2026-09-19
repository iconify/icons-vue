<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6dm1hgbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-reply" /></template>
<style>
.t6dm1hgbw {
  fill: currentColor;
  d: path("M10 9V7.41c0-.89-1.08-1.34-1.71-.71L3.7 11.29a.996.996 0 0 0 0 1.41l4.59 4.59c.63.63 1.71.19 1.71-.7V14.9c5 0 8.5 1.6 11 5.1c-1-5-4-10-11-11");
}

</style>
