<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnxdnwbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-inventory-2" /></template>
<style>
.qnxdnwbqt {
  fill: currentColor;
  d: path("M2 2v6.7h1V22h18V8.7h1V2zm13 12H9v-2h6zm5-7H4V4h16z");
}

</style>
