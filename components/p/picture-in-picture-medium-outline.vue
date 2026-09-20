<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbwsp-o5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:picture-in-picture-medium-outline" /></template>
<style>
.pbwsp-o5x {
  fill: currentColor;
  d: path("M2 20v-2h18V4h2v14q0 .825-.587 1.413T20 20zm6-4V8h10v8z");
}

</style>
