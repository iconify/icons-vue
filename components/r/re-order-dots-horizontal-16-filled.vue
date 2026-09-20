<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cvhg2fe3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:re-order-dots-horizontal-16-filled" /></template>
<style>
.cvhg2fe3c {
  fill: currentColor;
  d: path("M11 5.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 0 0-3 0m-4.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 0 0-3 0M3.5 7a1.5 1.5 0 1 1 0-3a1.5 1.5 0 0 1 0 3m7.5 3.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 0 0-3 0M8 12a1.5 1.5 0 1 1 0-3a1.5 1.5 0 0 1 0 3m-6-1.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 0 0-3 0");
}

</style>
