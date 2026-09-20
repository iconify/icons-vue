<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="zjc3web1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:warning-octagon-thin" /></template>
<style>
.zjc3web1r {
  fill: currentColor;
  d: path("M124 136V80a4 4 0 0 1 8 0v56a4 4 0 0 1-8 0m104-44.45v72.9a12 12 0 0 1-3.51 8.49l-51.55 51.55a12 12 0 0 1-8.49 3.51h-72.9a12 12 0 0 1-8.49-3.51l-51.55-51.55a12 12 0 0 1-3.51-8.49v-72.9a12 12 0 0 1 3.51-8.49l51.55-51.55A12 12 0 0 1 91.55 28h72.9a12 12 0 0 1 8.49 3.51l51.55 51.55a12 12 0 0 1 3.51 8.49m-8 0a4 4 0 0 0-1.17-2.83l-51.55-51.55a4.06 4.06 0 0 0-2.83-1.17h-72.9a4.06 4.06 0 0 0-2.83 1.17L37.17 88.72A4 4 0 0 0 36 91.55v72.9a4 4 0 0 0 1.17 2.83l51.55 51.55a4.06 4.06 0 0 0 2.83 1.17h72.9a4.06 4.06 0 0 0 2.83-1.17l51.55-51.55a4 4 0 0 0 1.17-2.83ZM128 164a8 8 0 1 0 8 8a8 8 0 0 0-8-8");
}

</style>
