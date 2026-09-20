<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfzpejbes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:picture-in-picture-rounded" /></template>
<style>
.mfzpejbes {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zm8-7h6q.425 0 .713-.288T19 12V8q0-.425-.288-.712T18 7h-6q-.425 0-.712.288T11 8v4q0 .425.288.713T12 13m3-3");
}

</style>
