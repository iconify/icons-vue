<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u53qms10b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:warehouse-outline" /></template>
<style>
.u53qms10b {
  fill: currentColor;
  d: path("M4 19h2v-8h12v8h2V8.35l-8-3.2l-8 3.2zm-2 2V7l10-4l10 4v14h-6v-8H8v8zm7 0v-2h2v2zm2-3v-2h2v2zm2 3v-2h2v2zM6 11h12z");
}

</style>
