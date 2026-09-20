<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvg529bcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stack-sharp" /></template>
<style>
.bvg529bcs {
  fill: currentColor;
  d: path("M6.616 14v1H3V3h12v3.616h-1V4H4v10zM9 21V9h12v12z");
}

</style>
