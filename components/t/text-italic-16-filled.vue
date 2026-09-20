<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="btuobxfoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-italic-16-filled" /></template>
<style>
.btuobxfoj {
  fill: currentColor;
  d: path("M12.8 2H7a.75.75 0 0 0 0 1.5h2.01l-3.428 9H3.2a.75.75 0 0 0 0 1.5H9a.75.75 0 0 0 0-1.5H7.188l3.428-9H12.8a.75.75 0 0 0 0-1.5");
}

</style>
