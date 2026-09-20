<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="xxiie10rz"/><path class="g3gsawfkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:plus" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g3gsawfkf {
  d: path("M9 5a1 1 0 0 1 2 0v10a1 1 0 1 1-2 0z");
}

.xxiie10rz {
  d: path("M5 11a1 1 0 1 1 0-2h10a1 1 0 1 1 0 2z");
}

</style>
