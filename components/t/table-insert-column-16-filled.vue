<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aep5i7cfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-insert-column-16-filled" /></template>
<style>
.aep5i7cfy {
  fill: currentColor;
  d: path("M3 2.5a.5.5 0 0 0-1 0v11a.5.5 0 0 0 1 0zm11 0a.5.5 0 0 0-1 0v11a.5.5 0 0 0 1 0zM6.5 2A1.5 1.5 0 0 0 5 3.5V5h6V3.5A1.5 1.5 0 0 0 9.5 2zM5 10V6h6v4zm0 1h6v1.5A1.5 1.5 0 0 1 9.5 14h-3A1.5 1.5 0 0 1 5 12.5z");
}

</style>
