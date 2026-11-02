<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtvf1bb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:more-grid-small-fill" /></template>
<style>
.xtvf1bb1t {
  fill: currentColor;
  d: path("M7.158 8.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m6 0a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m-6 6a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m6 0a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558");
}

</style>
