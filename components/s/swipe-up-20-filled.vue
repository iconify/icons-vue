<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ubkriownv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:swipe-up-20-filled" /></template>
<style>
.ubkriownv {
  fill: currentColor;
  d: path("M10.53 2.22a.75.75 0 0 0-1.06 0l-2.5 2.5a.75.75 0 0 0 1.06 1.06l1.22-1.22v9.69a.75.75 0 0 0 1.5 0V4.56l1.22 1.22a.75.75 0 1 0 1.06-1.06zM6 14a4 4 0 0 1 2.25-3.598v1.161a3 3 0 1 0 3.5 0v-1.16A4 4 0 1 1 6 14");
}

</style>
