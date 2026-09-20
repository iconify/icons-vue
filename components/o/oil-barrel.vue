<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_rzqcbst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:oil-barrel" /></template>
<style>
.p_rzqcbst {
  fill: currentColor;
  d: path("M4 21q-.425 0-.712-.288T3 20t.288-.712T4 19h1v-6H4q-.425 0-.712-.288T3 12t.288-.712T4 11h1V5H4q-.425 0-.712-.288T3 4t.288-.712T4 3h16q.425 0 .713.288T21 4t-.288.713T20 5h-1v6h1q.425 0 .713.288T21 12t-.288.713T20 13h-1v6h1q.425 0 .713.288T21 20t-.288.713T20 21zm10.125-5.863Q15 14.276 15 13.05q0-.975-.562-1.675T12 8.5q-1.875 2.15-2.437 2.863T9 13.05q0 1.225.875 2.088T12 16t2.125-.862");
}

</style>
