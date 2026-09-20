<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hyy09tkff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pipeline-20-regular" /></template>
<style>
.hyy09tkff {
  fill: currentColor;
  d: path("M2 5.5a1.5 1.5 0 1 1 3 0V6h10v-.5a1.5 1.5 0 0 1 3 0v9a1.5 1.5 0 0 1-3 0V14H5v.5a1.5 1.5 0 0 1-3 0zm2 0a.5.5 0 0 0-1 0v9a.5.5 0 0 0 1 0zM15 7H5v6h10zm2-1.5a.5.5 0 0 0-1 0v9a.5.5 0 0 0 1 0z");
}

</style>
