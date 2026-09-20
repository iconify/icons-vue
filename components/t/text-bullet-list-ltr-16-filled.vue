<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q9vt9tb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-bullet-list-ltr-16-filled" /></template>
<style>
.q9vt9tb1g {
  fill: currentColor;
  d: path("M2.25 5a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5m0 4.25a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5m1.25 3a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0M5.75 3a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 0-1.5zM5 8a.75.75 0 0 1 .75-.75h8.5a.75.75 0 0 1 0 1.5h-8.5A.75.75 0 0 1 5 8m.75 3.5a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 0-1.5z");
}

</style>
