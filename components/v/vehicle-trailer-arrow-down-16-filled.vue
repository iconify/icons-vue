<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d7usopbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vehicle-trailer-arrow-down-16-filled" /></template>
<style>
.d7usopbiy {
  fill: currentColor;
  d: path("M5.5 8a.5.5 0 0 1 .5.5v4.793l1.146-1.146a.5.5 0 1 1 .708.707l-2 2a.5.5 0 0 1-.708 0l-2-2a.5.5 0 1 1 .708-.707L5 13.293V8.5a.5.5 0 0 1 .5-.5m5-6A2.5 2.5 0 0 1 13 4.5V11h1V9.5a.5.5 0 0 1 1 0v4a.5.5 0 0 1-1 0V12H8.912A1.49 1.49 0 0 0 7 11.087V8.5a1.5 1.5 0 1 0-3 0v2.587a1.5 1.5 0 0 0-1.768.611A2.39 2.39 0 0 1 1 9.605C1 5.405 4.405 2 8.605 2zM9 4a1 1 0 0 0-1 1v1a1 1 0 0 0 1 1h1a1 1 0 0 0 1-1V5a1 1 0 0 0-1-1z");
}

</style>
