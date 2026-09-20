<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2tsm2b0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shield-toggle-sharp" /></template>
<style>
.b2tsm2b0y {
  fill: currentColor;
  d: path("M10 11h4q.825 0 1.413-.587T16 9t-.587-1.412T14 7h-4q-.825 0-1.412.588T8 9t.588 1.413T10 11m3.288-1.287Q13 9.425 13 9t.288-.712T14 8t.713.288T15 9t-.288.713T14 10t-.712-.288M10 16h4q.825 0 1.413-.587T16 14t-.587-1.412T14 12h-4q-.825 0-1.412.588T8 14t.588 1.413T10 16m-.712-1.287Q9 14.425 9 14t.288-.712T10 13t.713.288T11 14t-.288.713T10 15t-.712-.288M12 22q-3.475-.875-5.738-3.988T4 11.1V5l8-3l8 3v6.1q0 3.8-2.262 6.913T12 22");
}

</style>
