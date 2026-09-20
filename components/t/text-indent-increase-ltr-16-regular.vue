<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bv8gkk4dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-indent-increase-ltr-16-regular" /></template>
<style>
.bv8gkk4dm {
  fill: currentColor;
  d: path("M11.5 3a.5.5 0 0 1 0 1h-6a.5.5 0 0 1 0-1zm3 4a.5.5 0 0 1 0 1h-9a.5.5 0 0 1 0-1zm-5 4a.5.5 0 0 1 0 1h-4a.5.5 0 0 1 0-1zM1.854 5.646a.5.5 0 0 0-.708.708L2.293 7.5L1.146 8.646a.5.5 0 0 0 .708.708l1.5-1.5a.5.5 0 0 0 0-.708z");
}

</style>
