<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="f_swpep_d"/><path class="wj66j630h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:math-formula-16-regular" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f_swpep_d {
  d: path("M8.33 1.225A2.5 2.5 0 0 0 4.81 3.34L4.698 5H3.5a.5.5 0 0 0 0 1h1.132l-.44 6.595a1.5 1.5 0 0 1-2.112 1.268l-.375-.169a.5.5 0 0 0-.41.912l.375.17a2.5 2.5 0 0 0 3.52-2.114L5.634 6H7.5a.5.5 0 1 0 0-1H5.7l.107-1.595A1.5 1.5 0 0 1 7.92 2.137l.376.17a.5.5 0 1 0 .41-.913z");
}

.wj66j630h {
  d: path("M8.16 8.048a.25.25 0 0 1 .393.053l1.323 2.316l-2.73 2.73a.5.5 0 1 0 .708.707l2.537-2.537l1.188 2.079a1.25 1.25 0 0 0 1.969.263l.306-.305a.5.5 0 0 0-.708-.707l-.305.305a.25.25 0 0 1-.394-.052l-1.323-2.316l2.73-2.73a.5.5 0 1 0-.707-.707l-2.538 2.537l-1.188-2.08a1.25 1.25 0 0 0-1.969-.263l-.306.306a.5.5 0 1 0 .708.707z");
}

</style>
