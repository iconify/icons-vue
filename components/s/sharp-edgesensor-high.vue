<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wek4bsaxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-edgesensor-high" /></template>
<style>
.wek4bsaxb {
  fill: currentColor;
  d: path("M3 7h2v7H3zm-3 3h2v7H0zm22-3h2v7h-2zm-3 3h2v7h-2zm-1-8H6v20h12zm-2 15H8V7h8z");
}

</style>
