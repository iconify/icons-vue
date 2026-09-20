<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="fmvt3_0xq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-quote-opening-28-filled" /></template>
<style>
.fmvt3_0xq {
  fill: currentColor;
  d: path("M19.254 23a3.75 3.75 0 0 1-3.747-3.666l-.006-.084a16.4 16.4 0 0 1 2.621-8.969a15.7 15.7 0 0 1 1.808-2.306a12 12 0 0 1 .782-.75l.07-.058l.003-.003a.75.75 0 1 1 .937 1.172l-.005.005l-.033.027q-.047.04-.141.124a10 10 0 0 0-.527.518a14 14 0 0 0-1.633 2.084a14.8 14.8 0 0 0-2.042 4.931A3.75 3.75 0 1 1 19.254 23m-10.5 0a3.75 3.75 0 0 1-3.747-3.666L5 19.25a16.4 16.4 0 0 1 2.621-8.969A15.7 15.7 0 0 1 9.43 7.975a12 12 0 0 1 .782-.75l.07-.058l.003-.003a.75.75 0 1 1 .937 1.172l-.005.005l-.033.027q-.047.04-.141.124a10 10 0 0 0-.527.518a14 14 0 0 0-1.633 2.084a14.8 14.8 0 0 0-2.042 4.931A3.75 3.75 0 1 1 8.754 23");
}

</style>
