<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zdtxxnb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:white-small-square" /></template>
<style>
.zdtxxnb1b {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("M50.04 50.04h27.91v27.92H50.04z");
}

</style>
