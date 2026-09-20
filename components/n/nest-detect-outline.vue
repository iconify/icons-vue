<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1jahpbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:nest-detect-outline" /></template>
<style>
.r1jahpbvz {
  fill: currentColor;
  d: path("M9.5 22q-1.45 0-2.475-1.025T6 18.5V4q0-.825.588-1.412T8 2h3q.825 0 1.413.588T13 4v14.5q0 1.45-1.025 2.475T9.5 22M8 15.35q.35-.175.713-.262T9.5 15t.788.088t.712.262V4H8zM9.5 20q.625 0 1.063-.437T11 18.5t-.437-1.062T9.5 17t-1.062.438T8 18.5t.438 1.063T9.5 20m7.5-2q-.825 0-1.412-.587T15 16V8q0-.825.588-1.412T17 6h1q.825 0 1.413.588T20 8v8q0 .825-.587 1.413T18 18zm0-2h1V8h-1zM8 4h3zm9 12h1z");
}

</style>
