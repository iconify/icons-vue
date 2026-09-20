<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-pt_rbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:spatial-audio-sharp" /></template>
<style>
.j-pt_rbcq {
  fill: currentColor;
  d: path("M22.442 9.64q-1.665 0-3.18-.639q-1.516-.64-2.675-1.799q-1.16-1.16-1.8-2.675q-.639-1.515-.639-3.18h1.02q0 1.463.544 2.786t1.582 2.361t2.362 1.586t2.786.547zm0-4.513q-.755 0-1.447-.288q-.691-.289-1.224-.822q-.532-.532-.821-1.224t-.288-1.447h1.013q0 .548.209 1.063q.208.514.595.9q.386.387.9.593q.515.206 1.063.206zM10.096 12q-1.246 0-2.123-.877T7.096 9t.877-2.123T10.096 6t2.123.877T13.096 9t-.877 2.123t-2.123.877m-7 7.23v-1.645q0-.69.348-1.194t.983-.802q1.217-.593 2.702-.975q1.485-.383 2.967-.383q1.483 0 2.968.383q1.484.382 2.702.975q.634.298.982.802q.348.503.348 1.194v1.646z");
}

</style>
