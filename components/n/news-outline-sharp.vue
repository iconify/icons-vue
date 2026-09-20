<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnv1v1b1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:news-outline-sharp" /></template>
<style>
.qnv1v1b1g {
  fill: currentColor;
  d: path("M3 21V3h13l5 5v13zm2-2h14V9h-4V5H5zm2-2h10v-2H7zm0-8h5V7H7zm0 4h10v-2H7zM5 5v4zv14z");
}

</style>
