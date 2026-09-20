<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd8pp1b9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:timer-5-shutter-outline-rounded" /></template>
<style>
.bd8pp1b9x {
  fill: currentColor;
  d: path("M14 19H9.5q-.625 0-1.062-.437T8 17.5t.438-1.062T9.5 16H14v-2.5H9.5q-.625 0-1.062-.437T8 12V6.5q0-.625.438-1.062T9.5 5h6q.625 0 1.063.438T17 6.5t-.437 1.063T15.5 8H11v2.5h3q1.25 0 2.125.875T17 13.5V16q0 1.25-.875 2.125T14 19");
}

</style>
