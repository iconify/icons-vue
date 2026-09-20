<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exkmwtb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:transition-chop-sharp" /></template>
<style>
.exkmwtb9n {
  fill: currentColor;
  d: path("M3 19V5h18v14zm1.817-1H20V6h-4.844l2.248 8.692z");
}

</style>
