<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-5y0rbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:request-page" /></template>
<style>
.k-5y0rbcc {
  fill: currentColor;
  d: path("M11 18h2v-1h1q.425 0 .713-.288T15 16v-3q0-.425-.288-.712T14 12h-3v-1h4V9h-2V8h-2v1h-1q-.425 0-.712.288T9 10v3q0 .425.288.713T10 14h3v1H9v2h2zm-5 4q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h8l6 6v12q0 .825-.587 1.413T18 22z");
}

</style>
