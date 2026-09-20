<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8jr0zchf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:odt-sharp" /></template>
<style>
.d8jr0zchf {
  fill: currentColor;
  d: path("M5.308 14.692h3.384V9.308H5.308zm.884-.884v-3.616h1.616v3.616zm4.116.884h2.788l.596-.615V9.904l-.596-.596h-2.788zm.884-.884v-3.616h1.616v3.616zm5.174.884h.884v-4.5h1.25v-.884h-3.384v.884h1.25zM3 19V5h18v14z");
}

</style>
