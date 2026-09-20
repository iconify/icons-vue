<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="rqij2qbhb"/><path class="qdbki5r0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:o-button" /></template>
<style>
.qdbki5r0x {
  fill: var(--svg-color--fff, #fff);
  d: path("M63.97 13.82C34.03 13.82 12.3 34.92 12.3 64s21.73 50.19 51.67 50.19S115.63 93.08 115.63 64S93.91 13.82 63.97 13.82m0 74.53c-14.79 0-25.12-10.01-25.12-24.35s10.33-24.35 25.12-24.35S89.09 49.66 89.09 64S78.76 88.35 63.97 88.35");
}

.rqij2qbhb {
  fill: var(--svg-color--db4437, #db4437);
  d: path("M121 .11H6.99C3.21.11.12 3.21.12 6.99V121c0 3.79 3.09 6.88 6.87 6.88H121c3.78 0 6.88-3.09 6.88-6.88V6.99c0-3.78-3.1-6.88-6.88-6.88");
}

</style>
