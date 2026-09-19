<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="miz5pzb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-plus" /></template>
<style>
.miz5pzb0u {
  fill: currentColor;
  d: path("M19 12.998h-6v6h-2v-6H5v-2h6v-6h2v6h6z");
}

</style>
