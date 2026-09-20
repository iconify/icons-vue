<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx24pubtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:movie-info-rounded" /></template>
<style>
.sx24pubtj {
  fill: currentColor;
  d: path("M4 21q-.825 0-1.412-.587T2 19V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v14q0 .825-.587 1.413T20 21zm8.713-4.288Q13 16.426 13 16v-4q0-.425-.288-.712T12 11t-.712.288T11 12v4q0 .425.288.713T12 17t.713-.288M12 9q.425 0 .713-.288T13 8t-.288-.712T12 7t-.712.288T11 8t.288.713T12 9M4 19h2v-2H4zm14 0h2v-2h-2zM4 15h2v-2H4zm14 0h2v-2h-2zM4 11h2V9H4zm14 0h2V9h-2zM4 7h2V5H4zm14 0h2V5h-2z");
}

</style>
