<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm3dyih6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:other-houses-rounded" /></template>
<style>
.rm3dyih6p {
  fill: currentColor;
  d: path("M4 19v-7.375L3 12.4q-.35.25-.75.2t-.65-.4t-.187-.75t.387-.65l8.975-6.875q.275-.2.588-.3t.637-.1t.638.1t.587.3l9 6.875q.325.25.375.65t-.2.75q-.25.325-.65.375t-.725-.2L20 11.625V19q0 .825-.587 1.413T18 21H6q-.825 0-1.412-.587T4 19m4-4q.425 0 .713-.288T9 14t-.288-.712T8 13t-.712.288T7 14t.288.713T8 15m4 0q.425 0 .713-.288T13 14t-.288-.712T12 13t-.712.288T11 14t.288.713T12 15m4 0q.425 0 .713-.288T17 14t-.288-.712T16 13t-.712.288T15 14t.288.713T16 15");
}

</style>
