<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="dcyms0b_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:markdown-logo-thin" /></template>
<style>
.dcyms0b_k {
  fill: currentColor;
  d: path("M232 52H24a12 12 0 0 0-12 12v128a12 12 0 0 0 12 12h208a12 12 0 0 0 12-12V64a12 12 0 0 0-12-12m4 140a4 4 0 0 1-4 4H24a4 4 0 0 1-4-4V64a4 4 0 0 1 4-4h208a4 4 0 0 1 4 4Zm-112-88v48a4 4 0 0 1-8 0v-38.34l-25.17 25.17a4 4 0 0 1-5.66 0L60 113.66V152a4 4 0 0 1-8 0v-48a4 4 0 0 1 6.83-2.83L88 130.34l29.17-29.17A4 4 0 0 1 124 104m78.83 21.17a4 4 0 0 1 0 5.66l-24 24a4 4 0 0 1-5.66 0l-24-24a4 4 0 1 1 5.66-5.66L172 142.34V104a4 4 0 0 1 8 0v38.34l17.17-17.17a4 4 0 0 1 5.66 0");
}

</style>
