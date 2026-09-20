<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="giwswjaxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:subdirectory-arrow-right-outline" /></template>
<style>
.giwswjaxb {
  fill: currentColor;
  d: path("m14 21l-1.425-1.425l3.6-3.575H5V4h2v10h9.175l-3.6-3.6l1.4-1.425L20 15z");
}

</style>
