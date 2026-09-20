<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ss905-o2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speech-to-text-2-sharp" /></template>
<style>
.ss905-o2m {
  fill: currentColor;
  d: path("M7 10q-.85 0-1.425-.575T5 8V4q0-.85.575-1.425T7 2q.825 0 1.413.575T9 4v4q0 .85-.587 1.425T7 10m-1 6v-2.6q-1.775-.325-2.887-1.713T2 8.5h2q0 1.25.875 2.125T7 11.5t2.125-.875T10 8.5h2q0 1.8-1.112 3.188T8 13.4V16zm0 6v-4h11v-2h-7v-1h5v-2h-2.3q.775-1.35 1.038-3.137T14 6.5h-3V2h10v20z");
}

</style>
