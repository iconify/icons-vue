<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syji3kbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-map-pin-corner-fill-sharp" /></template>
<style>
.syji3kbuy {
  fill: currentColor;
  d: path("M17.997 10.082A6 6 0 0 0 17 10h-.003a6.01 6.01 0 0 0-5.909 4.967c-.201 1.161-.048 2.369.328 3.48l.001.003a1 1 0 0 1-.197.423l-2.187 2.75A1.002 1.002 0 0 1 7.25 21v-6H3a1 1 0 0 1-.783-1.623l8.75-11A1.002 1.002 0 0 1 12.75 3v6H17a1 1 0 0 1 .997 1.082m-2.813 10.695C13.952 19.518 13 17.798 13 16a4 4 0 0 1 .315-1.557c.2-.476.491-.907.857-1.271A3.98 3.98 0 0 1 17 12c1.064 0 2.078.418 2.828 1.172c.366.364.657.795.857 1.271c.209.492.316 1.022.315 1.557c0 2.286-1.588 4.594-3.445 5.832a1 1 0 0 1-1.11 0a8 8 0 0 1-1.261-1.055m1.11-4.069A1 1 0 0 0 17 17h.01a1 1 0 0 0 0-2H17a1 1 0 0 0-.925.621a.99.99 0 0 0 .216 1.085l.002.001Z");
}

</style>
