<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9u-rma7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-call-made" /></template>
<style>
.c9u-rma7q {
  fill: currentColor;
  d: path("M5.41 20L17 8.41V15h2V5H9v2h6.59L4 18.59z");
}

</style>
