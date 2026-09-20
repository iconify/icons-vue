<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1obs8zls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:publish" /></template>
<style>
.d1obs8zls {
  fill: currentColor;
  d: path("M11 20v-8.15l-2.6 2.6L7 13l5-5l5 5l-1.4 1.45l-2.6-2.6V20zM4 9V6q0-.825.588-1.412T6 4h12q.825 0 1.413.588T20 6v3h-2V6H6v3z");
}

</style>
