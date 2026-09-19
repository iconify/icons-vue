<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxwg4uncs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-checklist-rtl" /></template>
<style>
.xxwg4uncs {
  fill: currentColor;
  d: path("M11 8c0-.55-.45-1-1-1H3c-.55 0-1 .45-1 1s.45 1 1 1h7c.55 0 1-.45 1-1m0 8c0-.55-.45-1-1-1H3c-.55 0-1 .45-1 1s.45 1 1 1h7c.55 0 1-.45 1-1m6.05-5.71a.996.996 0 0 1-1.41 0l-2.12-2.12a.996.996 0 1 1 1.41-1.41l1.41 1.41l3.54-3.54a.996.996 0 1 1 1.41 1.41zm0 8a.996.996 0 0 1-1.41 0l-2.12-2.12a.996.996 0 1 1 1.41-1.41l1.41 1.41l3.54-3.54a.996.996 0 1 1 1.41 1.41z");
}

</style>
