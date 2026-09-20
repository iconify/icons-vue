<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fw1fhgfsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tv-with-assistant-outline" /></template>
<style>
.fw1fhgfsd {
  fill: currentColor;
  d: path("M11.213 12.213q.287-.288.287-.713t-.288-.712t-.712-.288t-.712.288t-.288.712t.288.713t.712.287t.713-.288m3 0q.287-.287.287-.712t-.288-.712t-.712-.288t-.712.288t-.288.712t.288.713t.712.287t.713-.288m-6 0q.287-.287.287-.712t-.288-.712T7.5 10.5t-.712.288t-.288.712t.288.713t.712.287t.713-.288m9 0q.287-.287.287-.712t-.288-.712t-.712-.288t-.712.288t-.288.712t.288.713t.712.287t.713-.288M4 21v-2q-.825 0-1.412-.587T2 17V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v11q0 .825-.587 1.413T20 19v2h-1l-.65-2H5.675L5 21zm0-4h16V6H4zm8-5.5");
}

</style>
