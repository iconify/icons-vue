<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okr8jm9nv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:widget-medium-rounded" /></template>
<style>
.okr8jm9nv {
  fill: currentColor;
  d: path("M3 8q-.425 0-.712-.288T2 7V3q0-.425.288-.712T3 2h11q.425 0 .713.288T15 3v4q0 .425-.288.713T14 8zm0 14q-.425 0-.712-.288T2 21v-4q0-.425.288-.712T3 16h4q.425 0 .713.288T8 17v4q0 .425-.288.713T7 22zm7 0q-.425 0-.712-.288T9 21v-4q0-.425.288-.712T10 16h4q.425 0 .713.288T15 17v4q0 .425-.288.713T14 22zm7 0q-.425 0-.712-.288T16 21v-4q0-.425.288-.712T17 16h4q.425 0 .713.288T22 17v4q0 .425-.288.713T21 22zM3 15q-.425 0-.712-.288T2 14v-4q0-.425.288-.712T3 9h4q.425 0 .713.288T8 10v4q0 .425-.288.713T7 15zm7 0q-.425 0-.712-.288T9 14v-4q0-.425.288-.712T10 9h4q.425 0 .713.288T15 10v4q0 .425-.288.713T14 15zm7 0q-.425 0-.712-.288T16 14v-4q0-.425.288-.712T17 9h4q.425 0 .713.288T22 10v4q0 .425-.288.713T21 15zm0-7q-.425 0-.712-.288T16 7V3q0-.425.288-.712T17 2h4q.425 0 .713.288T22 3v4q0 .425-.288.713T21 8z");
}

</style>
