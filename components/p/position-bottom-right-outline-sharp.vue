<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vezow1_wt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:position-bottom-right-outline-sharp" /></template>
<style>
.vezow1_wt {
  fill: currentColor;
  d: path("M9.385 16.808h8v-2h-8zM4 20V4h16v16zm1-1h14V5H5zM5 5v14z");
}

</style>
