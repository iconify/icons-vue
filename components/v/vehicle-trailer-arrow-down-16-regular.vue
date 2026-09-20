<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ldy0cpb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vehicle-trailer-arrow-down-16-regular" /></template>
<style>
.ldy0cpb3p {
  fill: currentColor;
  d: path("M5.5 8a.5.5 0 0 1 .5.5v4.793l1.146-1.146a.5.5 0 1 1 .708.707l-2 2a.5.5 0 0 1-.708 0l-2-2a.5.5 0 1 1 .708-.707L5 13.293V8.5a.5.5 0 0 1 .5-.5m5-6A2.5 2.5 0 0 1 13 4.5V11h1V9.5a.5.5 0 0 1 1 0v4a.5.5 0 0 1-1 0V12H8.945a1.5 1.5 0 0 0-.908-1H12V4.5A1.5 1.5 0 0 0 10.5 3H8.605A6.606 6.606 0 0 0 2 9.605c0 .662.462 1.215 1.08 1.358a1.5 1.5 0 0 0-.89.709A2.39 2.39 0 0 1 1 9.605C1 5.405 4.405 2 8.605 2zm-.398 2.005A1 1 0 0 1 11 5v2a1 1 0 0 1-1 1H8a1 1 0 0 1-.995-.897L7 7V5a1 1 0 0 1 1-1h2zM8 7h2V5H8z");
}

</style>
