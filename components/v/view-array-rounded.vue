<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qou9gjzbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-array-rounded" /></template>
<style>
.qou9gjzbq {
  fill: currentColor;
  d: path("M3 17.5v-11q0-.625.438-1.062T4.5 5t1.063.438T6 6.5v11q0 .625-.437 1.063T4.5 19t-1.062-.437T3 17.5M8.5 19q-.625 0-1.062-.437T7 17.5v-11q0-.625.438-1.062T8.5 5h7q.625 0 1.063.438T17 6.5v11q0 .625-.437 1.063T15.5 19zm9.5-1.5v-11q0-.625.438-1.062T19.5 5t1.063.438T21 6.5v11q0 .625-.437 1.063T19.5 19t-1.062-.437T18 17.5");
}

</style>
