<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u_7348h7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-right-16-filled" /></template>
<style>
.u_7348h7d {
  fill: currentColor;
  d: path("M5 3.75A.75.75 0 0 1 5.75 3h8.5a.75.75 0 0 1 0 1.5h-8.5A.75.75 0 0 1 5 3.75m-4 4A.75.75 0 0 1 1.75 7h12.5a.75.75 0 0 1 0 1.5H1.75A.75.75 0 0 1 1 7.75m8 4a.75.75 0 0 1 .75-.75h4.5a.75.75 0 0 1 0 1.5h-4.5a.75.75 0 0 1-.75-.75");
}

</style>
