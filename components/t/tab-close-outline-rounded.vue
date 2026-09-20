<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hizn19a5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tab-close-outline-rounded" /></template>
<style>
.hizn19a5m {
  fill: currentColor;
  d: path("M8 18q-.825 0-1.412-.587T6 16V4q0-.825.588-1.412T8 2h12q.825 0 1.413.588T22 4v12q0 .825-.587 1.413T20 18zm0-2h12V4H8zm-4 6q-.825 0-1.412-.587T2 20V7q0-.425.288-.712T3 6t.713.288T4 7v13h13q.425 0 .713.288T18 21t-.288.713T17 22zM8 4v12zm4.6 8.8l1.4-1.4l1.4 1.4q.275.275.7.275t.7-.275t.275-.7t-.275-.7L15.4 10l1.4-1.4q.275-.275.275-.7t-.275-.7t-.7-.275t-.7.275L14 8.6l-1.4-1.4q-.275-.275-.7-.275t-.7.275t-.275.7t.275.7l1.4 1.4l-1.4 1.4q-.275.275-.275.7t.275.7t.7.275t.7-.275");
}

</style>
