<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-zd_5xuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pause-fill" /></template>
<style>
.d-zd_5xuy {
  fill: currentColor;
  d: path("M6 2h1a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3m11 0h1a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3h-1a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3");
}

</style>
