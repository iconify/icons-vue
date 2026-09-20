<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="cqcvmbbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:presentation-chart-light" /></template>
<style>
.cqcvmbbgs {
  fill: currentColor;
  d: path("M216 42h-82V24a6 6 0 0 0-12 0v18H40a14 14 0 0 0-14 14v120a14 14 0 0 0 14 14h43.52l-24.21 30.25a6 6 0 0 0 9.38 7.5L98.88 190h58.24l30.19 37.75a6 6 0 0 0 9.38-7.5L172.48 190H216a14 14 0 0 0 14-14V56a14 14 0 0 0-14-14m2 134a2 2 0 0 1-2 2H40a2 2 0 0 1-2-2V56a2 2 0 0 1 2-2h176a2 2 0 0 1 2 2Zm-116-56v24a6 6 0 0 1-12 0v-24a6 6 0 0 1 12 0m32-16v40a6 6 0 0 1-12 0v-40a6 6 0 0 1 12 0m32-16v56a6 6 0 0 1-12 0V88a6 6 0 0 1 12 0");
}

</style>
