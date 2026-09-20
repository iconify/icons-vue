<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b767a7rrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:xbox-one-console-20-filled" /></template>
<style>
.b767a7rrt {
  fill: currentColor;
  d: path("M18 13a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-1h14zm-1-7a1 1 0 0 1 1 1v4H3a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1zm-1.75 2a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5");
}

</style>
