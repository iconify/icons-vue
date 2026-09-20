<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7e0iacuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:right-panel-close-sharp" /></template>
<style>
.p7e0iacuy {
  fill: currentColor;
  d: path("M8.404 15.173L11.596 12L8.404 8.827zM5 19h10V5H5zm-1 1V4h16v16z");
}

</style>
