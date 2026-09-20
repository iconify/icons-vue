<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svtciht6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:videogame-asset-sharp" /></template>
<style>
.svtciht6s {
  fill: currentColor;
  d: path("M3 17V7h18v10zm4.5-2.5h1v-2h2v-1h-2v-2h-1v2h-2v1h2zm7.707-.291q.293-.291.293-.707t-.291-.709t-.707-.293t-.709.291t-.293.707t.291.709t.707.293t.709-.291m3-3q.293-.291.293-.707t-.291-.709t-.707-.293t-.709.291t-.293.707t.291.709t.707.293t.709-.291");
}

</style>
