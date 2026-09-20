<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwd22hb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:personal-injury" /></template>
<style>
.wwd22hb7d {
  fill: currentColor;
  d: path("M9.877 8.777Q9 7.9 9 6.654t.877-2.123T12 3.654t2.123.877T15 6.654t-.877 2.123T12 9.654t-2.123-.877m.373 10.185q-.44 0-.749-.309t-.309-.75t.309-.748t.749-.309h2.592l-1.046 2.116zm-5.25 1V14.86q0-.639.367-1.169q.368-.53.964-.833q1.327-.654 2.757-1.006T12 11.5q.827 0 1.647.114q.82.113 1.603.345l-1.925 3.887H10.25q-.861 0-1.46.598q-.598.598-.598 1.46t.598 1.46t1.46.598zm11.239 0v-7.69q.374.124.727.268q.353.143.703.318q.596.304.964.833q.367.53.367 1.168v3.487q0 .671-.472 1.144t-1.144.472z");
}

</style>
