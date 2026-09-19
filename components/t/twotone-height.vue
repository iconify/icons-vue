<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3gkltbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-height" /></template>
<style>
.d3gkltbvj {
  fill: currentColor;
  d: path("M13 6.99h3L12 3L8 6.99h3v10.02H8L12 21l4-3.99h-3z");
}

</style>
