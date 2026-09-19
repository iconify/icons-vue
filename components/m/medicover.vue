<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ew0on226a"/><path class="i_ct5-1me"/><path class="fko8iszje"/><path class="x-4_ex3zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:medicover" /></template>
<style>
.ew0on226a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.26 14.53c10.737-4.425 19.863 1.408 23.786 9.221");
}

.fko8iszje {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.365 22.187c4.244-9.28 11.735-12.944 23.36-9.532M28.045 36.6c.576-7.487 8.232-9.74 15.455-11.474c-6.704.191-13.129-.062-19.5 4.888c-6.371-4.95-12.796-4.697-19.5-4.888c7.223 1.733 14.879 3.987 15.454 11.474z");
}

.i_ct5-1me {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.147 20.518c6.457-6.663 15.724-7.2 23.415-1.4");
}

.x-4_ex3zx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.53 24.621a2.53 2.53 0 0 1-5.06 0h0a2.53 2.53 0 1 1 5.06 0");
}

</style>
