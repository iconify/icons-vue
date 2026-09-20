<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m94qskb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:splitscreen-vertical-add-outline" /></template>
<style>
.m94qskb0u {
  fill: currentColor;
  d: path("M19 5h-4.025h.125h-.1zm-6 0q0-.825.588-1.412T15 3h4q.825 0 1.413.588T21 5v10h-2V5h-4v16q-.825 0-1.412-.587T13 19zM5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h4q.825 0 1.413.588T11 5v14q0 .825-.587 1.413T9 21zM9 5H5v14h4zm0 0H5zm10 18v-2h-2v-2h2v-2h2v2h2v2h-2v2z");
}

</style>
