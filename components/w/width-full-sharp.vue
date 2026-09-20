<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5363obow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:width-full-sharp" /></template>
<style>
.m5363obow {
  fill: currentColor;
  d: path("M3 19V5h18v14zm1-1h1.423V6H4zm14.577 0H20V6h-1.423z");
}

</style>
