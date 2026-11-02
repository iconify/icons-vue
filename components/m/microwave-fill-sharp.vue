<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmvpcebno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:microwave-fill-sharp" /></template>
<style>
.vmvpcebno {
  fill: currentColor;
  d: path("M2 18V4a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1h-3v1a1 1 0 0 1-2 0v-1H8v1a1 1 0 0 1-2 0v-1H3a1 1 0 0 1-1-1M6 8v6a1 1 0 0 0 1 1h6a1 1 0 0 0 1-1V8a1 1 0 0 0-1-1H7a1 1 0 0 0-1 1m12 6V8a1 1 0 0 0-2 0v6a1 1 0 0 0 2 0");
}

</style>
