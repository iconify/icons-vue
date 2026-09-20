<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ltfozk9zm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:number-eight-thin" /></template>
<style>
.ltfozk9zm {
  fill: currentColor;
  d: path("M147.08 119.64a44 44 0 1 0-38.16 0a52 52 0 1 0 38.16 0M92 80a36 36 0 1 1 36 36a36 36 0 0 1-36-36m36 132a44 44 0 1 1 44-44a44.05 44.05 0 0 1-44 44");
}

</style>
