<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcv-gf77s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-heart-outline-sharp" /></template>
<style>
.xcv-gf77s {
  fill: currentColor;
  d: path("M5 18.616v-1.647q0-.619.36-1.158q.361-.54.97-.838q1.359-.64 2.709-.98t2.711-.377q.004.096.021.173l.04.173q-.063.15-.095.322t-.031.332q-1.274.044-2.496.352q-1.222.309-2.381.882q-.38.202-.594.494Q6 16.637 6 16.97v.647h7.171l1 1zm4.877-8.108Q9 9.63 9 8.385t.877-2.123T12 5.385t2.123.877T15 8.385t-.877 2.123t-2.123.877t-2.123-.877m3.535-.711Q14 9.21 14 8.385t-.588-1.413T12 6.385t-1.413.587T10 8.385t.587 1.412t1.413.588t1.412-.588m4.122 8.819l-2.961-2.962q-.287-.287-.395-.597q-.109-.312-.109-.623q0-.68.483-1.21t1.24-.532q.602 0 .945.277q.344.277.798.731q.442-.442.79-.725t.961-.283q.781 0 1.248.532T21 14.436q0 .319-.121.638q-.121.318-.383.58z");
}

</style>
