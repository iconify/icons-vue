<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oq_v9fb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-list-rounded" /></template>
<style>
.oq_v9fb_l {
  fill: currentColor;
  d: path("M4 9q-.425 0-.712-.288T3 8V6q0-.425.288-.712T4 5h2q.425 0 .713.288T7 6v2q0 .425-.288.713T6 9zm5 0q-.425 0-.712-.288T8 8V6q0-.425.288-.712T9 5h11q.425 0 .713.288T21 6v2q0 .425-.288.713T20 9zm0 5q-.425 0-.712-.288T8 13v-2q0-.425.288-.712T9 10h11q.425 0 .713.288T21 11v2q0 .425-.288.713T20 14zm0 5q-.425 0-.712-.288T8 18v-2q0-.425.288-.712T9 15h11q.425 0 .713.288T21 16v2q0 .425-.288.713T20 19zm-5 0q-.425 0-.712-.288T3 18v-2q0-.425.288-.712T4 15h2q.425 0 .713.288T7 16v2q0 .425-.288.713T6 19zm0-5q-.425 0-.712-.288T3 13v-2q0-.425.288-.712T4 10h2q.425 0 .713.288T7 11v2q0 .425-.288.713T6 14z");
}

</style>
