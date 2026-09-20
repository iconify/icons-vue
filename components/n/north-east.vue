<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sndm-x75k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:north-east" /></template>
<style>
.sndm-x75k {
  fill: currentColor;
  d: path("M5.708 19L5 18.292L16.292 7H9V6h9v9h-1V7.708z");
}

</style>
