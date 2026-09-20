<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cb0t1xc0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:number-circle-4-48-filled" /></template>
<style>
.cb0t1xc0c {
  fill: currentColor;
  d: path("M24 44c11.046 0 20-8.954 20-20S35.046 4 24 4S4 12.954 4 24s8.954 20 20 20m3.5-29.42V27.5h2.25a1.25 1.25 0 1 1 0 2.5H27.5v2.75a1.25 1.25 0 1 1-2.5 0V30h-8.442c-1.235 0-1.974-1.375-1.293-2.405l9.209-13.925c.902-1.364 3.026-.726 3.026.91M25 17.406V27.5h-6.675z");
}

</style>
