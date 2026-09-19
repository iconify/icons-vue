<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qap61s_na"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-chevron-right" /></template>
<style>
.qap61s_na {
  fill: currentColor;
  d: path("M10 6L8.59 7.41L13.17 12l-4.58 4.59L10 18l6-6z");
}

</style>
