<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqy4k_biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-vertical-align-center" /></template>
<style>
.tqy4k_biv {
  fill: currentColor;
  d: path("M11 1v4H8l4 4l4-4h-3V1zM4 11h16v2H4zm4 8h3v4h2v-4h3l-4-4z");
}

</style>
