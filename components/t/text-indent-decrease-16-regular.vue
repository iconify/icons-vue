<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jx50mpt2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-indent-decrease-16-regular" /></template>
<style>
.jx50mpt2m {
  fill: currentColor;
  d: path("M11.5 3a.5.5 0 0 1 0 1h-6a.5.5 0 0 1 0-1zm3 4a.5.5 0 0 1 0 1h-9a.5.5 0 0 1 0-1zm-5 4a.5.5 0 0 1 0 1h-4a.5.5 0 0 1 0-1zM2.646 5.646a.5.5 0 0 1 .708.708L2.207 7.5l1.147 1.146a.5.5 0 0 1-.708.708l-1.5-1.5a.5.5 0 0 1 0-.708z");
}

</style>
