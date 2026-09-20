<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8p1ksbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:slideshow-outline-sharp" /></template>
<style>
.o8p1ksbcv {
  fill: currentColor;
  d: path("M9.885 15.577L15.462 12L9.885 8.423zM4 20V4h16v16zm1-1h14V5H5zm0 0V5z");
}

</style>
