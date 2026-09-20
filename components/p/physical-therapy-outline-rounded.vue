<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arjog6hhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:physical-therapy-outline-rounded" /></template>
<style>
.arjog6hhr {
  fill: currentColor;
  d: path("m13.979 19.922l-3.89-1.537H4.808q-.343 0-.576-.233T4 17.578v-2.193q0-1.67 1.165-2.835Q6.329 11.385 8 11.385h10.725q.533 0 .904.36q.371.362.371.89q0 .448-.263.781q-.264.334-.681.457l-2.864.771v3.779q0 .427-.19.773t-.511.57q-.326.222-.713.272t-.8-.116m-1.777-4.537H9.183q-.31 0-.503.196t-.238.436t.067.488q.11.247.414.354L14.346 19q.308.116.577-.067t.27-.51v-3.038zm-7.201 2h3.196q-.338-.208-.556-.534q-.217-.326-.217-.707q0-.722.519-1.24q.518-.52 1.24-.52h3.96L18.8 12.91q.125-.05.175-.125T19 12.61t-.088-.162t-.187-.062H8q-1.25 0-2.125.875T5 15.385zm2.877-8.262Q7 8.246 7 7t.877-2.123T10 4t2.123.877T13 7t-.877 2.123T10 10t-2.123-.877m3.536-.71Q12 7.825 12 7t-.587-1.412T10 5t-1.412.588T8 7t.588 1.413T10 9t1.413-.587M10 7");
}

</style>
