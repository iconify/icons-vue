<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uwvketboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:new-16-regular" /></template>
<style>
.uwvketboh {
  fill: currentColor;
  d: path("M3.502 11h5a.5.5 0 0 1 .09.992l-.09.008h-5a.5.5 0 0 1-.09-.992zh5zm1.646-5.854a.5.5 0 0 1 .638-.057l.07.058l3.998 4a.5.5 0 0 1-.638.764l-.07-.058l-3.998-4a.5.5 0 0 1 0-.707M11.502 3a.5.5 0 0 1 .491.41l.009.09v5a.5.5 0 0 1-.992.09l-.008-.09v-5a.5.5 0 0 1 .5-.5");
}

</style>
