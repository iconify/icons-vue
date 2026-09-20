<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pb80jwbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:toggle-multiple-24-regular" /></template>
<style>
.pb80jwbxt {
  fill: currentColor;
  d: path("M6.5 8.5a2 2 0 1 0 0-4a2 2 0 0 0 0 4m0-6.5h11a4.5 4.5 0 1 1 0 9h-11a4.5 4.5 0 0 1 0-9m11 1.5h-11a3 3 0 0 0 0 6h11a3 3 0 1 0 0-6m0 16a2 2 0 1 0 0-4a2 2 0 0 0 0 4M2 17.5A4.5 4.5 0 0 1 6.5 13h11a4.5 4.5 0 1 1 0 9h-11A4.5 4.5 0 0 1 2 17.5m4.5-3a3 3 0 1 0 0 6h11a3 3 0 1 0 0-6z");
}

</style>
