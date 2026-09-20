<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x957pnb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:picture-in-picture-alt-rounded" /></template>
<style>
.x957pnb5s {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zm8-3h6q.425 0 .713-.288T19 16v-4q0-.425-.288-.712T18 11h-6q-.425 0-.712.288T11 12v4q0 .425.288.713T12 17m3-3");
}

</style>
