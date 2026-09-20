<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj0y-0nyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:text-select-start-outline-rounded" /></template>
<style>
.pj0y-0nyi {
  fill: currentColor;
  d: path("M11.288 4.713Q11 4.425 11 4t.288-.712T12 3t.713.288T13 4t-.288.713T12 5t-.712-.288m4 0Q15 4.426 15 4t.288-.712T16 3t.713.288T17 4t-.288.713T16 5t-.712-.288m4 0Q19 4.426 19 4t.288-.712T20 3t.713.288T21 4t-.288.713T20 5t-.712-.288m0 4Q19 8.426 19 8t.288-.712T20 7t.713.288T21 8t-.288.713T20 9t-.712-.288m0 4Q19 12.426 19 12t.288-.712T20 11t.713.288T21 12t-.288.713T20 13t-.712-.288m0 4Q19 16.426 19 16t.288-.712T20 15t.713.288T21 16t-.288.713T20 17t-.712-.288m-8 4Q11 20.426 11 20t.288-.712T12 19t.713.288T13 20t-.288.713T12 21t-.712-.288m4 0Q15 20.426 15 20t.288-.712T16 19t.713.288T17 20t-.288.713T16 21t-.712-.288m4 0Q19 20.426 19 20t.288-.712T20 19t.713.288T21 20t-.288.713T20 21t-.712-.288M4 21q-.425 0-.712-.288T3 20t.288-.712T4 19h1V5H4q-.425 0-.712-.288T3 4t.288-.712T4 3h4q.425 0 .713.288T9 4t-.288.713T8 5H7v14h1q.425 0 .713.288T9 20t-.288.713T8 21z");
}

</style>
