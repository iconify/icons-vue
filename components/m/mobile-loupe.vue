<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_-ap8b8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-loupe" /></template>
<style>
.t_-ap8b8a {
  fill: currentColor;
  d: path("M16.5 22.5q-2.517 0-4.283-1.774t-1.72-4.3q.046-2.408 1.783-4.146q1.738-1.737 4.147-1.784q2.525-.046 4.299 1.72T22.5 16.5v4.385q0 .666-.475 1.14t-1.14.475zm-.442-3.5v-2.058h-1.933v-.884h1.933V14h.884v2.058h1.933v.884h-1.933V19zm-8.442 3q-.667 0-1.141-.475T6 20.386V3.615q0-.69.463-1.152T7.616 2h8.846q.666 0 1.14.475t.475 1.14v4.67q-.426-.083-.851-.129q-.426-.047-.851-.04q-3.353.049-5.781 2.47t-2.478 5.789q-.031 1.64.525 3.036q.555 1.395 1.611 2.589zm4.972-15.914q.22-.222.22-.549t-.222-.547t-.549-.22t-.548.22t-.22.55t.222.547t.549.22t.548-.22m7.455 13.954q1.457-1.459 1.457-3.543t-1.459-3.541t-3.543-1.457t-3.541 1.459t-1.457 3.543t1.459 3.541t3.543 1.457t3.541-1.459");
}

</style>
