<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j09p94pau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sim-card-lock" /></template>
<style>
.j09p94pau {
  fill: currentColor;
  d: path("M6 22q-.825 0-1.412-.587T4 20V8l6-6h8q.825 0 1.413.588T20 4v16q0 .825-.587 1.413T18 22zm4-6h4q.425 0 .713-.288T15 15v-3q0-.425-.288-.712T14 11v-1q0-.825-.587-1.412T12 8t-1.412.588T10 10v1q-.425 0-.712.288T9 12v3q0 .425.288.713T10 16m1-5v-1q0-.425.288-.712T12 9t.713.288T13 10v1z");
}

</style>
