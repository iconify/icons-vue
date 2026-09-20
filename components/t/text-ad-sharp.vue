<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g26-ovbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:text-ad-sharp" /></template>
<style>
.g26-ovbcj {
  fill: currentColor;
  d: path("M3 19V5h18v14zm2.73-3.116h12.54v-1H5.73zm0-3.384h12.54v-1H5.73zm0-3.384h8.77v-1H5.73z");
}

</style>
