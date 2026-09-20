<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ftap-_bei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nostra-map" /></template>
<style>
.ftap-_bei {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.165 20.988v-8.251l7.669 8.251v-8.251m5.753 4.125c0 5.293-4.292 9.583-9.588 9.583s-9.589-4.29-9.589-9.583c.001-5.292 4.294-9.583 9.59-9.582c5.295 0 9.588 4.29 9.588 9.582v.001m2.73-.029C36.394 10.023 30.794 4.5 24 4.5s-12.395 5.523-12.32 12.333C11.755 23.55 17.359 31.608 24 43.5c6.641-11.892 12.244-19.95 12.318-26.667");
}

</style>
