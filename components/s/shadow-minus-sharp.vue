<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khnqc1b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shadow-minus-sharp" /></template>
<style>
.khnqc1b-j {
  fill: currentColor;
  d: path("M2 22V6h4V2h16v16h-4v4zm6-6h12V4H8zm2-5V9h8v2z");
}

</style>
