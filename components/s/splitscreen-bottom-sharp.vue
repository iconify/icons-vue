<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykz5wobtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:splitscreen-bottom-sharp" /></template>
<style>
.ykz5wobtd {
  fill: currentColor;
  d: path("M4 19.385v-6h16v6zm0-8.77v-6h16v6zm15-5H5v4h14z");
}

</style>
