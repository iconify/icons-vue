<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vc30rmbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:waterfall-chart-rounded" /></template>
<style>
.vc30rmbue {
  fill: currentColor;
  d: path("M3.438 19.563Q3 19.125 3 18.5v-3q0-.625.438-1.062T4.5 14t1.063.438T6 15.5v3q0 .625-.437 1.063T4.5 20t-1.062-.437m5-6Q8 13.125 8 12.5v-2q0-.625.438-1.062T9.5 9t1.063.438T11 10.5v2q0 .625-.437 1.063T9.5 14t-1.062-.437m5-5Q13 8.124 13 7.5v-2q0-.625.438-1.062T14.5 4t1.063.438T16 5.5v2q0 .625-.437 1.063T14.5 9t-1.062-.437m5 11Q18 19.125 18 18.5v-13q0-.625.438-1.062T19.5 4t1.063.438T21 5.5v13q0 .625-.437 1.063T19.5 20t-1.062-.437");
}

</style>
