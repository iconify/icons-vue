<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yyq0l7bai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:select-all-off-20-regular" /></template>
<style>
.yyq0l7bai {
  fill: currentColor;
  d: path("M6 3a3 3 0 0 0-3 3v6a3 3 0 0 0 3 3h6a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3zM4 6a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2zm3.99 11a3 3 0 0 1-2.236-1h6.736a3.5 3.5 0 0 0 3.5-3.5v-1.201q.008-.15.008-.299V5.772c.61.549.992 1.344.992 2.228v4.5a4.5 4.5 0 0 1-4.5 4.5z");
}

</style>
