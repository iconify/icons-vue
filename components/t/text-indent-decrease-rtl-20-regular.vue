<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s_ci_5b3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-indent-decrease-rtl-20-regular" /></template>
<style>
.s_ci_5b3w {
  fill: currentColor;
  d: path("M5.5 4a.5.5 0 0 0 0 1h8a.5.5 0 0 0 0-1zm-3 5a.5.5 0 0 0 0 1h11a.5.5 0 0 0 0-1zM7 14.5a.5.5 0 0 1 .5-.5h6a.5.5 0 0 1 0 1h-6a.5.5 0 0 1-.5-.5m9.453-6.764a.5.5 0 1 0-.707.708l1.06 1.06l-1.06 1.06a.5.5 0 1 0 .707.708l1.414-1.414a.5.5 0 0 0 0-.707z");
}

</style>
