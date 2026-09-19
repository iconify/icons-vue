<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqwvaxbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-density-medium" /></template>
<style>
.zqwvaxbyk {
  fill: currentColor;
  d: path("M3 3h18v2H3zm0 16h18v2H3zm0-8h18v2H3z");
}

</style>
