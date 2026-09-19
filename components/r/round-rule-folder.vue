<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmdodwlkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-rule-folder" /></template>
<style>
.xmdodwlkd {
  fill: currentColor;
  d: path("M20 6h-8l-1.41-1.41C10.21 4.21 9.7 4 9.17 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2M7.12 15.29l-1.41-1.41a.996.996 0 1 1 1.41-1.41l.71.71l2.83-2.83a.996.996 0 1 1 1.41 1.41L8.53 15.3c-.39.38-1.02.38-1.41-.01M17.41 13l.88.88a.996.996 0 1 1-1.41 1.41l-.88-.88l-.88.88a.996.996 0 1 1-1.41-1.41l.88-.88l-.88-.88a.996.996 0 1 1 1.41-1.41l.88.88l.88-.88a.996.996 0 1 1 1.41 1.41z");
}

</style>
