<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icija0bln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:picture-in-picture-alt-sharp" /></template>
<style>
.icija0bln {
  fill: currentColor;
  d: path("M2 20V4h20v16zm9-3h8v-6h-8zm4-3");
}

</style>
