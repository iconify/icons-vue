<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okj4k6btb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:switch-off-rounded" /></template>
<style>
.okj4k6btb {
  fill: currentColor;
  d: path("M18 2q.825 0 1.413.588T20 4v16q0 .825-.587 1.413T18 22H6q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2zm-3 5H9q-.425 0-.712.288T8 8v8q0 .425.288.713T9 17h6q.425 0 .713-.288T16 16V8q0-.425-.288-.712T15 7m-1 2v4h-4V9zm-2 9.75q-.325 0-.537.213t-.213.537t.213.538t.537.212t.538-.213t.212-.537t-.213-.537T12 18.75m0-15q-.325 0-.537.213t-.213.537t.213.538t.537.212t.538-.213t.212-.537t-.213-.537T12 3.75");
}

</style>
