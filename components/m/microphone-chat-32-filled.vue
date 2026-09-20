<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m92emab9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:microphone-chat-32-filled" /></template>
<style>
.m92emab9t {
  fill: currentColor;
  d: path("M30 17a1 1 0 0 1 1 1c0 4.633-3.5 8.445-8 8.942V29a1 1 0 1 1-2 0v-2.058c-4.5-.497-8-4.31-8-8.942a1 1 0 1 1 2 0a7 7 0 1 0 14 0a1 1 0 0 1 1-1M13 2c2.782 0 5.32 1.034 7.258 2.737A6.5 6.5 0 0 0 15.5 11v5.003a2.5 2.5 0 0 0-4 1.997c0 2.227.696 4.29 1.879 5.99q-.189.008-.379.01c-1.658 0-3.23-.37-4.64-1.028l-3.872.968c-1.464.366-2.79-.96-2.425-2.424l.966-3.87A10.95 10.95 0 0 1 2 13C2 6.925 6.925 2 13 2m9 4a5 5 0 0 1 5 5v7a5 5 0 0 1-10 0v-7a5 5 0 0 1 5-5");
}

</style>
