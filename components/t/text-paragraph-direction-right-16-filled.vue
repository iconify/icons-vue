<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b9zx0sbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-paragraph-direction-right-16-filled" /></template>
<style>
.b9zx0sbma {
  fill: currentColor;
  d: path("M11 13.5V3h1v10.5a.5.5 0 0 0 1 0V3h.5a.5.5 0 0 0 0-1H9a3.5 3.5 0 1 0 0 7h1v4.5a.5.5 0 0 0 1 0M2.854 6.146a.5.5 0 1 0-.708.708L3.293 8L2.146 9.146a.5.5 0 1 0 .708.708l1.5-1.5a.5.5 0 0 0 0-.708z");
}

</style>
