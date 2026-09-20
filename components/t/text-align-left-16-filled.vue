<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n9ueu5_kg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-left-16-filled" /></template>
<style>
.n9ueu5_kg {
  fill: currentColor;
  d: path("M1 3.75A.75.75 0 0 1 1.75 3h8.5a.75.75 0 0 1 0 1.5h-8.5A.75.75 0 0 1 1 3.75m0 4A.75.75 0 0 1 1.75 7h12.5a.75.75 0 0 1 0 1.5H1.75A.75.75 0 0 1 1 7.75m0 4a.75.75 0 0 1 .75-.75h4.5a.75.75 0 0 1 0 1.5h-4.5a.75.75 0 0 1-.75-.75");
}

</style>
