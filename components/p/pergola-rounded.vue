<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0k9kobxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pergola-rounded" /></template>
<style>
.r0k9kobxt {
  fill: currentColor;
  d: path("M3 20V3q0-.425.288-.712T4 2t.713.288T5 3v1h14V3q0-.425.288-.712T20 2t.713.288T21 3v17q0 .425-.288.713T20 21t-.712-.288T19 20V10H5v10q0 .425-.288.713T4 21t-.712-.288T3 20m8 0v-2H9q-.425 0-.712-.288T8 17t.288-.712T9 16h6q.425 0 .713.288T16 17t-.288.713T15 18h-2v2q0 .425-.288.713T12 21t-.712-.288T11 20");
}

</style>
