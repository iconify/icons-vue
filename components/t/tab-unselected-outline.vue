<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tf4x4jbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tab-unselected-outline" /></template>
<style>
.tf4x4jbil {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18h2zm-2-4v-2h2v2zm0-4v-2h2v2zm0-4V6q0-.825.588-1.412T4 4h2v2H4v2zm4 12v-2h2v2zM8 6V4h2v2zm2 14v-2h2v2zm2-10V4h8q.825 0 1.413.588T22 6v4zm2 10v-2h2v2zm4 0v-2h2v-2h2v2q0 .825-.587 1.413T20 20zm2-6v-2h2v2z");
}

</style>
