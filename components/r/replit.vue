<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bc_idjjpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:replit" /></template>
<style>
.bc_idjjpz {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M7.75 15.5v-9a2 2 0 0 1 2-2H22a2 2 0 0 1 2 2v11H9.75a2 2 0 0 1-2-2Zm16.25 2h14.25a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2H24zm-16.25 24v-9a2 2 0 0 1 2-2H24v11a2 2 0 0 1-2 2H9.75a2 2 0 0 1-2-2Z");
}

</style>
