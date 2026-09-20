<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="lflju39am"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mic-prohibited-28-filled" /></template>
<style>
.lflju39am {
  fill: currentColor;
  d: path("M8.5 6.5a4.5 4.5 0 1 1 9 0v7.124a7.51 7.51 0 0 0-4.35 5.373L13 19a4.5 4.5 0 0 1-4.5-4.5zM13.016 21H13a6.5 6.5 0 0 1-6.5-6.5v-.75a.75.75 0 1 0-1.5 0v.75a8 8 0 0 0 7.25 7.965v2.785a.75.75 0 0 0 1.5 0v-1.477A7.5 7.5 0 0 1 13.016 21m7.484 6a6.5 6.5 0 1 0 0-13a6.5 6.5 0 0 0 0 13m0-1.5a4.98 4.98 0 0 1-2.965-.974l6.991-6.991A5 5 0 0 1 20.5 25.5m2.965-9.026l-6.991 6.991a5 5 0 0 1 6.991-6.991");
}

</style>
