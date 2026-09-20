<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vt-ylub3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pill" /></template>
<style>
.vt-ylub3o {
  fill: currentColor;
  d: path("m16.7 15.275l2.65-2.675q.8-.8 1.225-1.825T21 8.625q0-2.35-1.637-3.988T15.375 3q-1.125 0-2.15.425T11.4 4.65L8.725 7.3zM8.625 21q1.125 0 2.15-.425T12.6 19.35l2.675-2.65L7.3 8.725L4.65 11.4q-.8.8-1.225 1.825T3 15.375q0 2.35 1.638 3.987T8.625 21");
}

</style>
