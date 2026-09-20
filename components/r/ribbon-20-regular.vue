<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ywe70zb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ribbon-20-regular" /></template>
<style>
.ywe70zb2z {
  fill: currentColor;
  d: path("M16 8a6 6 0 0 1-2 4.472V17.5a.5.5 0 0 1-.748.434L10 16.076l-3.252 1.858A.5.5 0 0 1 6 17.5v-5.028A6 6 0 1 1 16 8m-6 6a6 6 0 0 1-3-.803v3.442l2.752-1.573a.5.5 0 0 1 .496 0L13 16.64v-3.442A6 6 0 0 1 10 14m0-1a5 5 0 1 0 0-10a5 5 0 0 0 0 10");
}

</style>
