<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppytd3vvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-doorbell-visitor" /></template>
<style>
.ppytd3vvb {
  fill: currentColor;
  d: path("M12 21.5q-1.864 0-3.182-1.316T7.5 17V7q0-1.868 1.316-3.184Q10.13 2.5 11.997 2.5t3.185 1.316T16.5 7v5h-2.884q-.667 0-1.141.475T12 13.615v.5q-.778 0-1.331.554T10.116 16q0 .754.553 1.296t1.331.588zm2.5 0v-.575q0-1.108 1.106-1.529T18 18.975t2.394.421t1.106 1.529v.575zm2.434-4.934q-.434-.433-.434-1.066t.434-1.066T18 14t1.066.434q.434.433.434 1.066t-.434 1.066Q18.633 17 18 17t-1.066-.434m-5.724.224q-.326-.326-.326-.79t.326-.79t.79-.325t.79.326t.326.789t-.326.79t-.79.326t-.79-.326m2.125-7.459q.55-.553.55-1.331t-.55-1.331T12 6.116t-1.336.553T10.117 8t.549 1.331T12 9.885t1.336-.554");
}

</style>
