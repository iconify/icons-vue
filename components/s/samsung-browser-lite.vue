<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="phn7zbbzc"/><path class="j8lpitbpi"/><path class="e0xem_bok"/><circle class="c_mzuqbrl"/><path class="hms-8cc7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:samsung-browser-lite" /></template>
<style>
.c_mzuqbrl {
  cx: 35.977px;
  cy: 35.255px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.e0xem_bok {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.604 19.785c4.23 2.93 6.541 6.402 5.738 9.399c-.237.884-.73 1.67-1.438 2.347m-12.882 2.93a40 40 0 0 1-7.481-1.28C10.858 30.319 3.3 23.887 4.659 18.817c.809-3.021 4.6-4.878 9.79-5.28");
}

.hms-8cc7w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.977 31.255v8h4");
}

.j8lpitbpi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.84 30.5c-2.423.033-5.288-.333-8.277-1.134c-7.566-2.028-13.056-6.074-12.263-9.038");
}

.phn7zbbzc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.25 37.196c-7.333 2.934-16.213-.761-18.784-8.94m-.19-7.846C12.3 12.74 20.22 8.222 27.852 10.381s12.011 10.158 9.718 17.752");
}

</style>
