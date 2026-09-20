<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uszbr4b5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pending-actions-outline-sharp" /></template>
<style>
.uszbr4b5r {
  fill: currentColor;
  d: path("M14.549 19.836Q13.385 18.67 13.385 17t1.164-2.835T17.384 13q1.672 0 2.836 1.165q1.165 1.164 1.165 2.835t-1.165 2.836T17.385 21t-2.836-1.164m4.492-.634l.546-.546l-1.818-1.818v-2.722H17v3.046zM4 20V4h6.252q.14-.586.623-.985q.483-.4 1.125-.4q.654 0 1.134.4q.48.398.62.985H20v7.635q-.258-.133-.488-.233T19 11.223V5h-3v2.23H8V5H5v14h6.742q.08.28.189.521q.11.24.28.479zm8.578-14.999q.23-.23.23-.578t-.23-.578t-.578-.23t-.578.23t-.23.578t.23.578t.578.23t.578-.23");
}

</style>
