<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1q62_blu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:split-scene-up-rounded" /></template>
<style>
.g1q62_blu {
  fill: currentColor;
  d: path("M6 21q-.825 0-1.412-.587T4 19v-3q0-.425.288-.712T5 15h14q.425 0 .713.288T20 16v3q0 .825-.587 1.413T18 21zm-3-8q-.425 0-.712-.288T2 12t.288-.712T3 11h1V5q0-.825.588-1.412T6 3h12q.825 0 1.413.588T20 5v6h1q.425 0 .713.288T22 12t-.288.713T21 13z");
}

</style>
