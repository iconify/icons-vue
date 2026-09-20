<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dawkwub6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:square-outline" /></template>
<style>
.dawkwub6v {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
