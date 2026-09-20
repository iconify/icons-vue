<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy4599b_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tab-outline-rounded" /></template>
<style>
.vy4599b_f {
  fill: currentColor;
  d: path("M4 18h16v-8h-6q-.425 0-.712-.288T13 9V6H4zm0 2q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zm0-2V6z");
}

</style>
