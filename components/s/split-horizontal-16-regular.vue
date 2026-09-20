<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b-th3ib7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:split-horizontal-16-regular" /></template>
<style>
.b-th3ib7g {
  fill: currentColor;
  d: path("M14.5 8a.5.5 0 0 0 0-1h-13a.5.5 0 0 0 0 1zM3 6h1V3a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v3h1V3a2 2 0 0 0-2-2H5a2 2 0 0 0-2 2zm0 6V9h1v3a1 1 0 0 0 1 1h6a1 1 0 0 0 1-1V9h1v3a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2");
}

</style>
