<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fedp45b1j"/><path class="to4-aac-c"/><path class="l5n9ndbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zara" /></template>
<style>
.fedp45b1j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 20.849v-4.853h9.707L4.755 32.004h11.156v-4.342");
}

.l5n9ndbpn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.404 23.83c13.965 0 5.535 7.323 11.751 8.09c.852.084 1.788-.171 2.384-.852M23.404 15.996h2.64c7.493 0 7.493 7.748 0 7.748h-2.64m5.194 8.26h2.81");
}

.to4-aac-c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.823 32.004l5.961-16.008l5.62 16.008h-3.832m3.832 0h3.832m-13.369-5.62h7.493m8.686 5.62l5.961-16.008l5.62 16.008h-2.896m1.959 0h2.81m-11.41-5.62h7.493m-16.179 5.62V15.996h-2.555");
}

</style>
