<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h41n_yf0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vip-32-filled" /></template>
<style>
.h41n_yf0x {
  fill: currentColor;
  d: path("M25.5 4A4.5 4.5 0 0 1 30 8.5v15a4.5 4.5 0 0 1-4.5 4.5h-19A4.5 4.5 0 0 1 2 23.5v-15A4.5 4.5 0 0 1 6.5 4zm-12.635 7.57a1 1 0 0 0-1.296.565L9.5 17.402l-2.07-5.267a1 1 0 0 0-1.86.73l2.658 6.768a1.367 1.367 0 0 0 2.545 0l2.658-6.768a1 1 0 0 0-.566-1.296M16 11.5a1 1 0 0 0-1 1v7a1 1 0 1 0 2 0v-7a1 1 0 0 0-1-1m4 0a1 1 0 0 0-1 1v7a1 1 0 1 0 2 0V18h1.75a3.25 3.25 0 0 0 0-6.5zm2.75 2a1.25 1.25 0 1 1 0 2.5H21v-2.5z");
}

</style>
