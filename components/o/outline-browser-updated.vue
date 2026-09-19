<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsvouobtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-browser-updated" /></template>
<style>
.hsvouobtl {
  fill: currentColor;
  d: path("M22 13v3c0 1.1-.9 2-2 2h-3l1 1v2H6v-2l1-1H4c-1.1 0-2-.9-2-2V5c0-1.1.9-2 2-2h8v2H4v11h16v-3zm-7 2l-5-5l1.41-1.41L14 11.17V3h2v8.17l2.59-2.58L20 10z");
}

</style>
