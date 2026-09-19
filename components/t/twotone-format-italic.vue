<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmfalhmpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-format-italic" /></template>
<style>
.qmfalhmpb {
  fill: currentColor;
  d: path("M6 15v3h8v-3h-2.21l3.42-8H18V4h-8v3h2.21l-3.42 8z");
}

</style>
