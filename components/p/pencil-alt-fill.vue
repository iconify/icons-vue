<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmegaibiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-alt-fill" /></template>
<style>
.wmegaibiv {
  fill: currentColor;
  d: path("m3.293 15.293l11-11a2.414 2.414 0 0 1 3.414 0l2 2a2.414 2.414 0 0 1 0 3.414l-11 11A1 1 0 0 1 8 21H4a1 1 0 0 1-1-1v-4c0-.265.105-.52.293-.707");
}

</style>
