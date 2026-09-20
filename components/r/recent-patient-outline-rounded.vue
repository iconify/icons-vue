<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmg9snbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:recent-patient-outline-rounded" /></template>
<style>
.jmg9snbzc {
  fill: currentColor;
  d: path("M6.039 18.616q-.441 0-.74-.3Q5 18.017 5 17.577v-.608q0-.619.36-1.158q.361-.54.97-.838q1.416-.679 2.834-1.018q1.417-.34 2.836-.34q.564 0 1.124.061t1.124.182q.189.05.317.195q.127.145.127.348q0 .215-.166.348q-.166.134-.376.084q-.533-.121-1.065-.17q-.533-.047-1.085-.047q-1.335 0-2.646.318t-2.546.916q-.38.202-.593.494Q6 16.637 6 16.97v.647h8.192q.213 0 .356.143q.144.144.144.357t-.144.356t-.356.144zm-.039-1h8.692zm3.877-7.108Q9 9.63 9 8.385t.877-2.123T12 5.385t2.123.877T15 8.385t-.877 2.123t-2.123.877t-2.123-.877m3.535-.711Q14 9.21 14 8.385t-.588-1.413T12 6.385t-1.413.587T10 8.385t.587 1.412t1.413.588t1.412-.588m5.088 8.51h-.615q-.344 0-.576-.23t-.232-.57V14.3q0-.34.232-.57t.576-.23h2.313q.341 0 .522.292t.019.59l-1.373 2.734h.776q.349 0 .523.298t.012.595l-1.798 3.377q-.081.137-.23.106T18.5 21.3z");
}

</style>
