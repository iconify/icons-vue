<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e68te4bek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-array-sharp" /></template>
<style>
.e68te4bek {
  fill: currentColor;
  d: path("M3 19V5h3v14zm4 0V5h10v14zm11 0V5h3v14z");
}

</style>
