<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="po49j3b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:tablet-mac" /></template>
<style>
.po49j3b3e {
  fill: currentColor;
  d: path("M18.5 0h-14A2.5 2.5 0 0 0 2 2.5v19A2.5 2.5 0 0 0 4.5 24h14a2.5 2.5 0 0 0 2.5-2.5v-19A2.5 2.5 0 0 0 18.5 0m-7 23c-.83 0-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5s1.5.67 1.5 1.5s-.67 1.5-1.5 1.5m7.5-4H4V3h15z");
}

</style>
