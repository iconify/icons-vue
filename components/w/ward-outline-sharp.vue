<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xo77s6bzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ward-outline-sharp" /></template>
<style>
.xo77s6bzo {
  fill: currentColor;
  d: path("M4 4H2V2h4v20H4zm3 18V2h13v20zm2-11.475q.45-.275.95-.4T11 10h5q.55 0 1.05.125t.95.4V4H9zm3.088-2.113Q11.5 7.825 11.5 7t.588-1.412T13.5 5t1.413.588T15.5 7t-.587 1.413T13.5 9t-1.412-.587M9 20h9v-6q0-.825-.587-1.412T16 12h-5q-.825 0-1.412.588T9 14zm3.5-1h2v-2h2v-2h-2v-2h-2v2h-2v2h2zM9 20h9z");
}

</style>
