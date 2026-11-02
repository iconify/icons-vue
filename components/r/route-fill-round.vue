<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkq05rbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:route-fill-round" /></template>
<style>
.jkq05rbht {
  fill: currentColor;
  d: path("M15.171 7H9a2 2 0 1 0 0 4h6a4 4 0 0 1 0 8H8.829a3 3 0 1 1 0-2H15a2 2 0 1 0 0-4H9a4 4 0 0 1 0-8h6.171a3 3 0 1 1 0 2");
}

</style>
