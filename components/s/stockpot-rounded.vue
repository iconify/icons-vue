<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcpasab8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stockpot-rounded" /></template>
<style>
.lcpasab8m {
  fill: currentColor;
  d: path("M6 20q-1.25 0-2.125-.875T3 17V9q0-.425.288-.712T4 8h16q.425 0 .713.288T21 9v8q0 1.25-.875 2.125T18 20zM9 5V4q0-.425.288-.712T10 3h4q.425 0 .713.288T15 4v1h5q.425 0 .713.288T21 6t-.288.713T20 7H4q-.425 0-.712-.288T3 6t.288-.712T4 5z");
}

</style>
