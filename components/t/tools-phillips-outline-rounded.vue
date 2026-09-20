<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmshwzbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tools-phillips-outline-rounded" /></template>
<style>
.dmshwzbnf {
  fill: currentColor;
  d: path("M8 21q-.425 0-.712-.288T7 20t.288-.712T8 19h8q.425 0 .713.288T17 20t-.288.713T16 21zm0-3q-.425 0-.712-.288T7 17V8.675q0-.325.1-.625t.3-.575L10.45 3.4q.15-.2.35-.3t.45-.1h1.5q.25 0 .45.1t.35.3l3.05 4.075q.2.275.3.575t.1.625V17q0 .425-.288.713T16 18zm1-2h6v-2.175l-3-3l-3 3zm0-5l2-2V6L9 8.675zm6 0V8.675L13 6v3zm0 5H9z");
}

</style>
