<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gisuwpb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-width-full" /></template>
<style>
.gisuwpb2l {
  fill: currentColor;
  d: path("M22 4H2v16h20zM4 6h1v12H4zm16 12h-1V6h1z");
}

</style>
