<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1pb7mb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:thumb-up-rounded" /></template>
<style>
.u1pb7mb4w {
  fill: currentColor;
  d: path("M21 8q.8 0 1.4.6T23 10v2q0 .175-.038.375t-.112.375l-3 7.05q-.225.5-.75.85T18 21h-8q-.825 0-1.412-.587T8 19V8.825q0-.4.163-.762t.437-.638l5.425-5.4q.375-.35.888-.425t.987.175t.688.7t.087.925L15.55 8zM4 21q-.825 0-1.412-.587T2 19v-9q0-.825.588-1.412T4 8t1.413.588T6 10v9q0 .825-.587 1.413T4 21");
}

</style>
