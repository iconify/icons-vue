<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jpkgv9tyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:play-16-regular" /></template>
<style>
.jpkgv9tyu {
  fill: currentColor;
  d: path("M5.745 3.064A.5.5 0 0 0 5 3.5v9a.5.5 0 0 0 .745.436l8-4.5a.5.5 0 0 0 0-.871zM4 3.5a1.5 1.5 0 0 1 2.235-1.307l8 4.5a1.5 1.5 0 0 1 0 2.615l-8 4.5A1.5 1.5 0 0 1 4 12.5z");
}

</style>
