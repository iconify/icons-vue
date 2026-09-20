<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="niv-62xzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mention-28-filled" /></template>
<style>
.niv-62xzu {
  fill: currentColor;
  d: path("M14 2c6.627 0 12 5.373 12 12c0 3.636-1.993 5.97-4.5 5.97c-1.509 0-2.83-.845-3.645-2.31c-.99 1.407-2.543 2.34-4.355 2.34c-3.134 0-5.5-2.788-5.5-6s2.366-6 5.5-6c1.353 0 2.562.52 3.5 1.368V9a1 1 0 1 1 2 0v5c0 2.99 1.507 3.97 2.5 3.97S24 16.99 24 14c0-5.523-4.477-10-10-10S4 8.477 4 14s4.477 10 10 10c1.226 0 2.4-.223 3.485-.628c.405-.15.866-.072 1.171.233c.49.491.366 1.316-.28 1.57A12 12 0 0 1 14 26C7.373 26 2 20.627 2 14S7.373 2 14 2m-.5 8c-1.836 0-3.5 1.69-3.5 4s1.664 4 3.5 4s3.5-1.69 3.5-4s-1.664-4-3.5-4");
}

</style>
