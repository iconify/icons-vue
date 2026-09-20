<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpv7o7png"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:trail-length-rounded" /></template>
<style>
.lpv7o7png {
  fill: currentColor;
  d: path("M8 17q-.425 0-.712-.288T7 16t.288-.712T8 15h5q-.35-.425-.562-.925T12.1 13H10q-.425 0-.712-.288T9 12t.288-.712T10 11h2.1q.125-.575.338-1.075T13 9H4q-.425 0-.712-.288T3 8t.288-.712T4 7h13q2.075 0 3.538 1.463T22 12t-1.463 3.538T17 17zm-5-4q-.425 0-.712-.288T2 12t.288-.712T3 11h4q.425 0 .713.288T8 12t-.288.713T7 13zm1 4q-.425 0-.712-.288T3 16t.288-.712T4 15h1q.425 0 .713.288T6 16t-.288.713T5 17z");
}

</style>
