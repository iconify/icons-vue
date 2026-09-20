<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j392d5-bs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:split-scene-down" /></template>
<style>
.j392d5-bs {
  fill: currentColor;
  d: path("M4 9V5q0-.825.588-1.412T6 3h12q.825 0 1.413.588T20 5v4zm2 12q-.825 0-1.412-.587T4 19v-6H2v-2h20v2h-2v6q0 .825-.587 1.413T18 21z");
}

</style>
