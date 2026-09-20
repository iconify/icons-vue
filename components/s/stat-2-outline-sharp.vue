<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwmkc2zcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stat-2-outline-sharp" /></template>
<style>
.qwmkc2zcp {
  fill: currentColor;
  d: path("M7.4 17.708L6.692 17L12 11.692L17.308 17l-.708.708l-4.6-4.594zm0-6L6.692 11L12 5.692L17.308 11l-.708.708L12 7.114z");
}

</style>
