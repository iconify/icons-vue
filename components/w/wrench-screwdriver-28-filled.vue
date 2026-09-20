<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="cc2fnb0ci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:wrench-screwdriver-28-filled" /></template>
<style>
.cc2fnb0ci {
  fill: currentColor;
  d: path("M11.367 2.805a.75.75 0 0 1 .742-.014A6.498 6.498 0 0 1 11 14.683V24l-.01.204A2 2 0 0 1 7 24v-9.317A6.499 6.499 0 0 1 5.89 2.79A.75.75 0 0 1 7 3.449V6.5l.01.204A2 2 0 0 0 9 8.5l.204-.01A2 2 0 0 0 11 6.5V3.45c0-.265.14-.51.367-.645M25 22a4 4 0 0 1-8 0v-3.5h8zM22.183 2.007a.75.75 0 0 1 .554.379l1.25 2.25a.75.75 0 0 1 .03.669l-.935 2.104V14h1.168a.75.75 0 0 1 .75.75V17h-8v-2.25a.75.75 0 0 1 .75-.75h1.332V7.41l-.936-2.105a.75.75 0 0 1 .03-.67l1.25-2.25l.055-.084A.75.75 0 0 1 20.082 2h2z");
}

</style>
