<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="km1q15bnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:previous-16-filled" /></template>
<style>
.km1q15bnw {
  fill: currentColor;
  d: path("M14 3.002a1 1 0 0 0-1.578-.816l-7 4.963a1 1 0 0 0-.007 1.628l7 5.037A1 1 0 0 0 14 13.003zM2 2.5a.5.5 0 0 1 1 0v11a.5.5 0 0 1-1 0z");
}

</style>
