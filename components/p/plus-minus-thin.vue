<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mgaii8b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:plus-minus-thin" /></template>
<style>
.mgaii8b9z {
  fill: currentColor;
  d: path("m202.83 58.83l-144 144a4 4 0 0 1-5.66-5.66l144-144a4 4 0 1 1 5.66 5.66M68 112a4 4 0 0 0 8 0V76h36a4 4 0 0 0 0-8H76V32a4 4 0 0 0-8 0v36H32a4 4 0 0 0 0 8h36Zm156 68h-80a4 4 0 0 0 0 8h80a4 4 0 0 0 0-8");
}

</style>
