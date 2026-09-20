<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="e6-inebgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:small-orange-diamond" /></template>
<style>
.e6-inebgr {
  fill: var(--svg-color--ff9800, #ff9800);
  d: path("M64 92.16c-.68 0-1.37-.26-1.89-.78L36.6 65.87a2.67 2.67 0 0 1 0-3.77l25.51-25.52c1-.99 2.77-1 3.77 0L91.4 62.1c.5.5.78 1.17.78 1.88s-.28 1.38-.78 1.88L65.88 91.38c-.52.52-1.2.78-1.88.78");
}

</style>
