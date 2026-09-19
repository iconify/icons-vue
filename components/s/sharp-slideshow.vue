<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egn1wmbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-slideshow" /></template>
<style>
.egn1wmbzo {
  fill: currentColor;
  d: path("M10 8v8l5-4zm11-5H3v18h18zm-2 16H5V5h14z");
}

</style>
