<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4bdcdbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-loupe-outline-sharp" /></template>
<style>
.o4bdcdbfp {
  fill: currentColor;
  d: path("M7 21V3v5.14v-.025zm5.588-14.914q.22-.222.22-.549t-.222-.547t-.549-.22t-.548.22t-.22.55t.222.547t.549.22t.548-.22M10.252 22H6V2h12.077v6.285q-.252-.053-.498-.083t-.502-.061V3H7v18h2.446q.165.287.368.516q.203.228.438.484m6.246.5q-2.516 0-4.282-1.774t-1.72-4.3q.047-2.408 1.784-4.146t4.147-1.784q2.525-.046 4.299 1.72t1.774 4.282V22.5zm3.545-2.459q1.457-1.459 1.457-3.543t-1.459-3.541t-3.543-1.457t-3.541 1.459t-1.457 3.543t1.459 3.541t3.543 1.457t3.541-1.459M16.058 19v-2.058h-1.933v-.884h1.933V14h.884v2.058h1.933v.884h-1.933V19z");
}

</style>
