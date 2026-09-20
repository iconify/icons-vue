<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="easkv_bwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-compact-alt-rounded" /></template>
<style>
.easkv_bwo {
  fill: currentColor;
  d: path("M8.5 16.5h2q.425 0 .713-.288t.287-.712v-2q0-.425-.288-.712T10.5 12.5h-2q-.425 0-.712.288T7.5 13.5v2q0 .425.288.713t.712.287m0-5h2q.425 0 .713-.288t.287-.712v-2q0-.425-.288-.712T10.5 7.5h-2q-.425 0-.712.288T7.5 8.5v2q0 .425.288.713t.712.287m5 5h2q.425 0 .713-.288t.287-.712v-2q0-.425-.288-.712T15.5 12.5h-2q-.425 0-.712.288t-.288.712v2q0 .425.288.713t.712.287m0-5h2q.425 0 .713-.288t.287-.712v-2q0-.425-.288-.712T15.5 7.5h-2q-.425 0-.712.288T12.5 8.5v2q0 .425.288.713t.712.287M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20z");
}

</style>
