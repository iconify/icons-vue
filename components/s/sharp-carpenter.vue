<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-wgnhbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-carpenter" /></template>
<style>
.c-wgnhbbu {
  fill: currentColor;
  d: path("M7 1.5L3.11 5.39l8.13 11.67l-1.41 1.41l4.24 4.24l7.07-7.07zm5.66 16.97l4.24-4.24l1.41 1.41l-4.24 4.24z");
}

</style>
