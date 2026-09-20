<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q1u3w1f_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-bullet-list-rtl-16-regular" /></template>
<style>
.q1u3w1f_m {
  fill: currentColor;
  d: path("M14 4.5a1 1 0 1 1 0-2a1 1 0 0 1 0 2M14 9a1 1 0 1 1 0-2a1 1 0 0 1 0 2m-1 3.5a1 1 0 1 0 2 0a1 1 0 0 0-2 0M10.5 3a.5.5 0 0 1 0 1h-9a.5.5 0 0 1 0-1zm.5 5a.5.5 0 0 0-.5-.5h-9a.5.5 0 0 0 0 1h9A.5.5 0 0 0 11 8m-.5 4a.5.5 0 0 1 0 1h-9a.5.5 0 0 1 0-1z");
}

</style>
