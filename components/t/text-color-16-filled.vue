<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vj3_6vb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-color-16-filled" /></template>
<style>
.vj3_6vb3b {
  fill: currentColor;
  d: path("M12.5 10a1.5 1.5 0 0 1 1.5 1.5v2a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 2 13.5v-2A1.5 1.5 0 0 1 3.5 10zM8 .5c.3 0 .571.179.69.454l3 7a.75.75 0 0 1-1.38.592L9.648 7H6.352l-.663 1.546a.75.75 0 0 1-1.378-.592l3-7l.051-.099A.75.75 0 0 1 8 .5m-1.005 5h2.01L8 3.154z");
}

</style>
