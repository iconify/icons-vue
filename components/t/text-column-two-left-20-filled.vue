<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fvvih5asf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-column-two-left-20-filled" /></template>
<style>
.fvvih5asf {
  fill: currentColor;
  d: path("M3 5.75A.75.75 0 0 1 3.75 5h2.5a.75.75 0 0 1 0 1.5h-2.5A.75.75 0 0 1 3 5.75m6 0A.75.75 0 0 1 9.75 5h6.5a.75.75 0 0 1 0 1.5h-6.5A.75.75 0 0 1 9 5.75m-6 3A.75.75 0 0 1 3.75 8h2.5a.75.75 0 0 1 0 1.5h-2.5A.75.75 0 0 1 3 8.75m6 0A.75.75 0 0 1 9.75 8h6.5a.75.75 0 0 1 0 1.5h-6.5A.75.75 0 0 1 9 8.75m-6 3a.75.75 0 0 1 .75-.75h2.5a.75.75 0 0 1 0 1.5h-2.5a.75.75 0 0 1-.75-.75m6 0a.75.75 0 0 1 .75-.75h6.5a.75.75 0 0 1 0 1.5h-6.5a.75.75 0 0 1-.75-.75m-6 3a.75.75 0 0 1 .75-.75h2.5a.75.75 0 0 1 0 1.5h-2.5a.75.75 0 0 1-.75-.75m6 0a.75.75 0 0 1 .75-.75h6.5a.75.75 0 0 1 0 1.5h-6.5a.75.75 0 0 1-.75-.75");
}

</style>
