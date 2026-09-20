<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3gbdirsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:timer-10-alt-1-outline-sharp" /></template>
<style>
.p3gbdirsz {
  fill: currentColor;
  d: path("M9.058 16.635h1v-7.27H7.904v1h1.154zm2.769 0h4.27v-7.27h-4.27zm1-1v-5.25h2.27v5.25zM9.385 2.5v-1h5.23v1zm-.497 17.874q-1.455-.626-2.546-1.716t-1.716-2.545T4 13t.626-3.113t1.716-2.545t2.546-1.716T12 5q1.454 0 2.812.52t2.492 1.469l1.092-1.093l.708.708l-1.092 1.092q.95 1.135 1.469 2.493T20 13q0 1.658-.626 3.113t-1.716 2.545t-2.546 1.716T12 21t-3.113-.626m8.063-2.424Q19 15.9 19 13t-2.05-4.95T12 6T7.05 8.05T5 13t2.05 4.95T12 20t4.95-2.05M12 13");
}

</style>
