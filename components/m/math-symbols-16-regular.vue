<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k2gcfbbad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:math-symbols-16-regular" /></template>
<style>
.k2gcfbbad {
  fill: currentColor;
  d: path("M4.5 2a.5.5 0 0 1 .5.5V4h1.5a.5.5 0 0 1 0 1H5v1.5a.5.5 0 0 1-1 0V5H2.5a.5.5 0 0 1 0-1H4V2.5a.5.5 0 0 1 .5-.5m5 2a.5.5 0 0 0 0 1h4a.5.5 0 0 0 0-1zm-4.293 7.5l1.647-1.646a.5.5 0 1 0-.708-.708L4.5 10.793L2.854 9.146a.5.5 0 1 0-.708.708L3.793 11.5l-1.647 1.646a.5.5 0 0 0 .708.708L4.5 12.207l1.646 1.647a.5.5 0 0 0 .708-.708zM11.5 10a1 1 0 1 0 0-2a1 1 0 0 0 0 2m-2 .5a.5.5 0 0 0 0 1h4a.5.5 0 0 0 0-1zm3 2.5a1 1 0 1 1-2 0a1 1 0 0 1 2 0");
}

</style>
