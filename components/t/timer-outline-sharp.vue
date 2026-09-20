<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnxndxbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:timer-outline-sharp" /></template>
<style>
.cnxndxbbb {
  fill: currentColor;
  d: path("M9.385 2.5v-1h5.23v1zM11.5 13.616h1V8.385h-1zm-2.612 6.758q-1.455-.626-2.546-1.716t-1.716-2.545T4 13t.626-3.113t1.716-2.545t2.546-1.716T12 5q1.454 0 2.812.52t2.492 1.469l1.092-1.093l.708.708l-1.092 1.092q.95 1.135 1.469 2.493T20 13q0 1.658-.626 3.113t-1.716 2.545t-2.546 1.716T12 21t-3.113-.626m8.063-2.424Q19 15.9 19 13t-2.05-4.95T12 6T7.05 8.05T5 13t2.05 4.95T12 20t4.95-2.05M12 13");
}

</style>
