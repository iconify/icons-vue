<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="q92i-xrwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:square-logo-thin" /></template>
<style>
.q92i-xrwp {
  fill: currentColor;
  d: path("M208 36H48a12 12 0 0 0-12 12v160a12 12 0 0 0 12 12h160a12 12 0 0 0 12-12V48a12 12 0 0 0-12-12m4 172a4 4 0 0 1-4 4H48a4 4 0 0 1-4-4V48a4 4 0 0 1 4-4h160a4 4 0 0 1 4 4ZM160 92H96a4 4 0 0 0-4 4v64a4 4 0 0 0 4 4h64a4 4 0 0 0 4-4V96a4 4 0 0 0-4-4m-4 64h-56v-56h56Z");
}

</style>
