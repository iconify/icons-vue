<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbmoemj_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:web-asset-off-rounded" /></template>
<style>
.qbmoemj_p {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4v2.85L1.35 4.2q-.3-.3-.3-.712t.3-.713t.713-.3t.712.3l18.4 18.4q.3.3.3.7t-.3.7t-.712.3t-.713-.3L17.15 20zm0-2h11.15l-10-10H4zM22 6v11q0 .5-.312.75T21 18t-.687-.262t-.313-.763V8h-8.325q-.4 0-.763-.15t-.637-.425L8.55 5.7q-.225-.25-.275-.525t.075-.55t.35-.45T9.275 4H20q.825 0 1.413.588T22 6");
}

</style>
