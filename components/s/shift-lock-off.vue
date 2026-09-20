<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgmhbgb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shift-lock-off" /></template>
<style>
.fgmhbgb2w {
  fill: currentColor;
  d: path("M4 22v-2h16v2zm4-4v-5H3l4.5-5.525l8.5 8.5V18zm7.85-5L8.775 5.925L12 2l9 11zm4.625 10.3L.675 3.5L2.1 2.075l19.8 19.8z");
}

</style>
