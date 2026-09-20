<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="veluvebuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:toggle-left-20-regular" /></template>
<style>
.veluvebuc {
  fill: currentColor;
  d: path("M6 12a2 2 0 1 1 0-4a2 2 0 0 1 0 4m12-2a4 4 0 0 0-4-4H6a4 4 0 1 0 0 8h8a4 4 0 0 0 4-4m-4-3a3 3 0 1 1 0 6H6a3 3 0 1 1 0-6z");
}

</style>
