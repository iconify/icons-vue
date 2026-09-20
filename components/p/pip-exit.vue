<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="morewv2qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pip-exit" /></template>
<style>
.morewv2qe {
  fill: currentColor;
  d: path("m17.075 16.5l1.425-1.425L15.4 12H18v-2h-6v6h2v-2.575zM2 9V4h7v5zm0 2h9V4h9q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20H4q-.825 0-1.412-.587T2 18z");
}

</style>
