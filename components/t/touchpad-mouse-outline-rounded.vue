<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_aluzbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:touchpad-mouse-outline-rounded" /></template>
<style>
.n_aluzbqu {
  fill: currentColor;
  d: path("M18.975 18.975Q20 17.95 20 16.5v-2h-7v2q0 1.45 1.025 2.475T16.5 20t2.475-1.025m-5.97-5.475H16v-3.446q-1.315.179-2.137 1.146t-.857 2.3m3.994 0h2.994q-.034-1.333-.856-2.3T17 10.054zm-3.688 6.189Q12 18.377 12 16.5v-3q0-1.877 1.312-3.189T16.5 9t3.189 1.312T21 13.5v3q0 1.877-1.311 3.189T16.5 21t-3.189-1.311M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5H20.5q.214 0 .357.143T21 5.5t-.143.357T20.5 6H4.616q-.27 0-.443.173T4 6.616v10.769q0 .269.173.442t.443.173H9.12q.213 0 .357.143q.143.143.143.357t-.143.357T9.12 19zM4 18V6z");
}

</style>
