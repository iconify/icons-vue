<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9fffob2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-plus-minus" /></template>
<style>
.x9fffob2b {
  fill: currentColor;
  d: path("M19 10.998h-6v6h-2v-6H5v-2h6v-6h2v6h6zm0 10H5v-2h14z");
}

</style>
