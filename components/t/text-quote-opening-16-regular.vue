<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a9opj7bek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-quote-opening-16-regular" /></template>
<style>
.a9opj7bek {
  fill: currentColor;
  d: path("M5 12a1 1 0 1 1 0-2a1 1 0 0 1 0 2m-.885-2.794c.23-1.592.852-2.966 2.239-4.352a.5.5 0 1 0-.708-.708C3.527 6.266 3 8.408 3 11a2 2 0 1 0 1.115-1.794M11 12a1 1 0 1 1 0-2a1 1 0 0 1 0 2m-.885-2.794c.23-1.592.852-2.966 2.239-4.352a.5.5 0 0 0-.708-.708C9.527 6.266 9 8.408 9 11a2 2 0 1 0 1.115-1.794");
}

</style>
