<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bab9eo8pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-center-16-filled" /></template>
<style>
.bab9eo8pu {
  fill: currentColor;
  d: path("M3 3.75A.75.75 0 0 1 3.75 3h8.5a.75.75 0 0 1 0 1.5h-8.5A.75.75 0 0 1 3 3.75m-2 4A.75.75 0 0 1 1.75 7h12.5a.75.75 0 0 1 0 1.5H1.75A.75.75 0 0 1 1 7.75m4 4a.75.75 0 0 1 .75-.75h4.5a.75.75 0 0 1 0 1.5h-4.5a.75.75 0 0 1-.75-.75");
}

</style>
