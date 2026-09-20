<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ut-5exw6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tag-48-filled" /></template>
<style>
.ut-5exw6e {
  fill: currentColor;
  d: path("M23.49 7.245A4.25 4.25 0 0 1 26.495 6h11.257a4.25 4.25 0 0 1 4.25 4.25v11.257a4.25 4.25 0 0 1-1.245 3.006l-16.24 16.24a4.25 4.25 0 0 1-6.01 0L7.248 29.495a4.25 4.25 0 0 1 0-6.01zM33.5 17a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5");
}

</style>
