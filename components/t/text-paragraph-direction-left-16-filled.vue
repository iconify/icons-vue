<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uimop1bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-paragraph-direction-left-16-filled" /></template>
<style>
.uimop1bwl {
  fill: currentColor;
  d: path("M11 13.5V3h1v10.5a.5.5 0 0 0 1 0V3h.5a.5.5 0 0 0 0-1H9a3.5 3.5 0 1 0 0 7h1v4.5a.5.5 0 0 0 1 0M3.854 6.854a.5.5 0 1 0-.708-.708l-1.5 1.5a.5.5 0 0 0 0 .708l1.5 1.5a.5.5 0 0 0 .708-.708L2.707 8z");
}

</style>
