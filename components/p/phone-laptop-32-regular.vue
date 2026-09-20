<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="phjwukp4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:phone-laptop-32-regular" /></template>
<style>
.phjwukp4w {
  fill: currentColor;
  d: path("M6 8a3 3 0 0 1 3-3h16a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3h-8v-2h8a1 1 0 0 0 1-1V8a1 1 0 0 0-1-1H9a1 1 0 0 0-1 1H7q-.519.002-1 .126zm23 17H17v-2h12a1 1 0 1 1 0 2M9 25a1 1 0 1 0 0-2a1 1 0 0 0 0 2M3 13a3 3 0 0 1 3-3h6a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3zm3-1a1 1 0 0 0-1 1v12a1 1 0 0 0 1 1h6a1 1 0 0 0 1-1V13a1 1 0 0 0-1-1z");
}

</style>
