<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yddwn2bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:patient-check-in" /></template>
<style>
.yddwn2bph {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16 1.75H8q-1.76 0-3.005 1.245T3.75 6v12q0 1.76 1.245 3.005T8 22.25h8q1.76 0 3.005-1.245T20.25 18V6q0-1.76-1.245-3.005T16 1.75m-7.25 2.5h6.5q2.5 0 2.5 2.5v4.5q0 2.5-2.5 2.5h-6.5q-2.5 0-2.5-2.5v-4.5q0-2.5 2.5-2.5m.5 11.25h5.5q.621 0 1.061.439q.439.44.439 1.061t-.439 1.061q-.44.439-1.061.439h-5.5q-1.5 0-1.5-1.5t1.5-1.5");
}

</style>
