<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzd_9fbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:subtitles-outline" /></template>
<style>
.kzd_9fbof {
  fill: currentColor;
  d: path("M6 16h8v-2H6zm10 0h2v-2h-2zM6 12h2v-2H6zm4 0h8v-2h-8zm-6 8q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zm0-2h16V6H4zm0 0V6z");
}

</style>
