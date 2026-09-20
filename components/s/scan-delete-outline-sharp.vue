<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnych2b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:scan-delete-outline-sharp" /></template>
<style>
.fnych2b4k {
  fill: currentColor;
  d: path("M6 4v5zv16v-.238V20zM4 22V2h10l6 6v4.35q-.475-.175-.975-.262T18 12V9h-5V4H6v16h6.35q.2.575.5 1.075t.7.925zm11.9-.5l-1.4-1.4l2.1-2.1l-2.1-2.1l1.4-1.4l2.1 2.1l2.1-2.1l1.4 1.4l-2.075 2.1l2.075 2.1l-1.4 1.4l-2.1-2.075z");
}

</style>
