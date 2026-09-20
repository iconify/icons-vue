<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnq686cxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speech-to-text-2-outline-sharp" /></template>
<style>
.pnq686cxe {
  fill: currentColor;
  d: path("M19 4v16zM6 22v-4h2v2h11V4h-8V2h10v20zm1-12q-.85 0-1.425-.575T5 8V4q0-.85.575-1.425T7 2q.825 0 1.413.575T9 4v4q0 .85-.587 1.425T7 10m-1 6v-2.6q-1.775-.325-2.887-1.713T2 8.5h2q0 1.25.875 2.125T7 11.5t2.125-.875T10 8.5h2q0 1.8-1.112 3.188T8 13.4V16zm4 2h7v-2h-7zm0-3h5v-2h-5z");
}

</style>
