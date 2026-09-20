<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2hb1d6dv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tools-level-outline-sharp" /></template>
<style>
.s2hb1d6dv {
  fill: currentColor;
  d: path("M4 17q-.825 0-1.412-.587T2 15V9q0-.825.588-1.412T4 7h16q.825 0 1.413.588T22 9v6q0 .825-.587 1.413T20 17zm0-2h16V9h-2.35q.175.35.263.725T18 10.5q0 1.425-1.038 2.463T14.5 14h-5q-1.425 0-2.463-1.037T6 10.5q0-.4.088-.775T6.35 9H4zm5.5-3H11V9H9.5q-.6 0-1.05.45T8 10.5t.45 1.05T9.5 12m3.5 0h1.5q.6 0 1.05-.45T16 10.5t-.45-1.05T14.5 9H13zm7 3H4z");
}

</style>
