<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8y_4bc_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:switch-camera-outline-rounded" /></template>
<style>
.f8y_4bc_v {
  fill: currentColor;
  d: path("M4 21q-.825 0-1.412-.587T2 19V7q0-.825.588-1.412T4 5h3.15L8.4 3.65q.275-.3.663-.475T9.875 3h4.25q.425 0 .813.175t.662.475L16.85 5H20q.825 0 1.413.588T22 7v12q0 .825-.587 1.413T20 21zm0-2h16V7h-4.05l-1.825-2h-4.25L8.05 7H4zm4.85-4.95h6.3l-.85.85q-.275.275-.275.7t.275.7t.7.275t.7-.275l2.6-2.6q.3-.3.3-.7t-.3-.7l-2.6-2.6q-.275-.275-.687-.287T14.3 9.7q-.275.275-.288.688t.263.712l.925.95H8.8l.925-.95q.275-.275.275-.687T9.7 9.7q-.275-.275-.7-.275t-.7.275l-2.6 2.6q-.3.3-.3.7t.3.7l2.6 2.6q.275.275.7.275t.7-.275t.275-.7t-.275-.7z");
}

</style>
