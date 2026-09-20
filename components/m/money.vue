<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="juk8swb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:money" /></template>
<style>
.juk8swb4v {
  fill: currentColor;
  d: path("M15 16h3q.425 0 .713-.288T19 15V9q0-.425-.288-.712T18 8h-3q-.425 0-.712.288T14 9v6q0 .425.288.713T15 16m1-2v-4h1v4zm-7 2h3q.425 0 .713-.288T13 15V9q0-.425-.288-.712T12 8H9q-.425 0-.712.288T8 9v6q0 .425.288.713T9 16m1-2v-4h1v4zm-5 2h2V8H5zm-3 4V4h20v16z");
}

</style>
