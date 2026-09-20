<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftukapb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:metro-sharp" /></template>
<style>
.ftukapb8x {
  fill: currentColor;
  d: path("M3 21V3h4.05L12 16.05L16.9 3H21v18h-3V8.75L13.275 21h-2.55L6 8.825V21z");
}

</style>
