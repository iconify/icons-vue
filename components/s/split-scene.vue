<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m76uogbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:split-scene" /></template>
<style>
.m76uogbjb {
  fill: currentColor;
  d: path("M5 20q-.825 0-1.412-.587T3 18V6q0-.825.588-1.412T5 4h4v16zm6 2V2h2v2h6q.825 0 1.413.588T21 6v12q0 .825-.587 1.413T19 20h-6v2z");
}

</style>
