<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yg4y83-sx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:title-outline-rounded" /></template>
<style>
.yg4y83-sx {
  fill: currentColor;
  d: path("M10.5 7h-4q-.625 0-1.062-.437T5 5.5t.438-1.062T6.5 4h11q.625 0 1.063.438T19 5.5t-.437 1.063T17.5 7h-4v11.5q0 .625-.437 1.063T12 20t-1.062-.437T10.5 18.5z");
}

</style>
