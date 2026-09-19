<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2co_66rt"/><path class="ro_b6zg8s"/><path class="y9q5j_tzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:opay" /></template>
<style>
.g2co_66rt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.16 28c1.66 4.94 6.34 8.5 11.84 8.5c6.9 0 12.5-5.6 12.5-12.5S30.9 11.5 24 11.5c-5.5 0-10.18 3.56-11.84 8.5");
}

.ro_b6zg8s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.88 20C4.75 10.04 13.5 2.5 24 2.5c11.87 0 21.5 9.63 21.5 21.5S35.87 45.5 24 45.5C13.5 45.5 4.75 37.96 2.88 28");
}

.y9q5j_tzp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.5 20h10v8h-10z");
}

</style>
