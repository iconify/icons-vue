<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="gjyu_zbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:shower-bold" /></template>
<style>
.gjyu_zbyj {
  fill: currentColor;
  d: path("M68 236a16 16 0 1 1-16-16a16 16 0 0 1 16 16m16-48a16 16 0 1 0 16 16a16 16 0 0 0-16-16m-64 0a16 16 0 1 0 16 16a16 16 0 0 0-16-16m32 0a16 16 0 1 0-16-16a16 16 0 0 0 16 16M256 40a12 12 0 0 1-12 12h-23l-25.81 25.79l-21.45 125.54a20 20 0 0 1-33.86 10.8l-98-98a20 20 0 0 1 10.84-33.88l125.5-21.44l29.29-29.3A12 12 0 0 1 216 28h28a12 12 0 0 1 12 12m-86.68 46.68l-105 17.94l87.07 87.07Z");
}

</style>
