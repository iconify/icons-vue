<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ic7_-fb5t"/><path class="kqdet7svm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myexpenses" /></template>
<style>
.ic7_-fb5t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.5 8.5v9a2 2 0 0 0 2 2h9v18a2 2 0 0 1-2 2h-35a2 2 0 0 1-2-2v-27a2 2 0 0 1 2-2Zm11 11l-11-11");
}

.kqdet7svm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.99 30H20l4-6l-3.99-6H28m13.62-.38V6a1.69 1.69 0 0 0-1.9-1.68L6.5 8.5");
}

</style>
