<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="j2raqq3sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:subset-of-bold" /></template>
<style>
.j2raqq3sz {
  fill: currentColor;
  d: path("M212 208a12 12 0 0 1-12 12H48a12 12 0 0 1 0-24h152a12 12 0 0 1 12 12m-12-52h-96a44 44 0 0 1 0-88h96a12 12 0 0 0 0-24h-96a68 68 0 0 0 0 136h96a12 12 0 0 0 0-24");
}

</style>
