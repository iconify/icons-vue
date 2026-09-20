<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yclwbzbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:photo-frame-outline-sharp" /></template>
<style>
.yclwbzbry {
  fill: currentColor;
  d: path("M4.846 19.423V18H2V5h20v13h-2.846v1.423zM3 17h18V6H3zm3.404-2.5h11.212l-3.5-4.673l-3.116 4l-2.096-2.539zM3 17V6z");
}

</style>
