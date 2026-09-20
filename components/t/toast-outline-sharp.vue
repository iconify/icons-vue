<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxs5cdm3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:toast-outline-sharp" /></template>
<style>
.zxs5cdm3x {
  fill: currentColor;
  d: path("M6.5 17.5h11v-1h-11zM4 20V4h16v16zm1-1h14V5H5zm0 0V5z");
}

</style>
