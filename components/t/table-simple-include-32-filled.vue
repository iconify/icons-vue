<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h7q3-4qai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-simple-include-32-filled" /></template>
<style>
.h7q3-4qai {
  fill: currentColor;
  d: path("M15 14.786q-.11.103-.214.214H3V7.5A4.5 4.5 0 0 1 7.5 3H15zM3 17h10.666a4.8 4.8 0 0 0-.166 1.25v7.5c0 1.257.488 2.4 1.286 3.25H7.5A4.5 4.5 0 0 1 3 24.5zm26-9.5v7.286a4.73 4.73 0 0 0-3.25-1.286h-7.5q-.651.002-1.25.166V3h7.5A4.5 4.5 0 0 1 29 7.5M15 18.25A3.25 3.25 0 0 1 18.25 15h7.5A3.25 3.25 0 0 1 29 18.25v7.5A3.25 3.25 0 0 1 25.75 29h-7.5A3.25 3.25 0 0 1 15 25.75z");
}

</style>
