<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h10_rqlzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:new-window-outline-sharp" /></template>
<style>
.h10_rqlzb {
  fill: currentColor;
  d: path("M3 21V3h8v2H5v14h14v-6h2v8zm13-10V8h-3V6h3V3h2v3h3v2h-3v3z");
}

</style>
