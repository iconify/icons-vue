<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vtb-2zbyf"/><g class="y9tr6bcfx"><path class="xedv7nbnr"/><path class="yydv0xbga"/></g><g class="h01tyzbfu"><path class="fq9i93b8p"/><path class="qkq0adc_z"/><circle class="xj9silbon"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qq" /></template>
<style>
.fq9i93b8p {
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.596 18.119c-1.016-1.379-4.662-1.73-7.588-1.73s-6.572.351-7.588 1.73c2.287 1.594 5.853 2.292 7.588 2.279s5.301-.685 7.588-2.28m-8.649-5.744c0 1.722-.98 3.119-2.19 3.119h0c-1.21 0-2.19-1.397-2.19-3.12s.98-3.118 2.19-3.118s2.19 1.396 2.19 3.119m6.503 0c0 1.722-.98 3.119-2.19 3.119h0c-1.21 0-2.19-1.397-2.19-3.12s.98-3.118 2.19-3.118h0c1.21 0 2.19 1.396 2.19 3.119");
}

.h01tyzbfu {
  fill: none;
  stroke: currentColor;
}

.qkq0adc_z {
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.957 12.769c.732-.714 1.497-.688 2.167-.37");
}

.vtb-2zbyf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.084 25.28a50 50 0 0 0 6.357 1.4v5.667h0c1.904.587 3.451.396 5.332.226v-5.348q1.14.055 2.235.055c4.354 0 9.317-.66 13.91-1.995m-1.768-4.209c-4.077 1.016-8.341 1.518-12.142 1.518c-3.805 0-8.076-.504-12.157-1.522m3.663 19.344c-7.93 2.724-2.357 3.723 6.608 2.678m10.369-2.682c7.95 2.728 2.37 3.728-6.606 2.68");
}

.xedv7nbnr {
  d: path("M11.917 20.913c-1.838 4.532-5.221 11.201-4.004 15.792c1.687-1.518 2.222-2.385 3.346-4.095c.05 4.61 4.766 10.595 12.741 10.595S36.692 37.22 36.74 32.61c1.125 1.71 1.66 2.577 3.347 4.095c1.217-4.59-2.166-11.26-4.004-15.792C37.06 10.989 31.607 4.463 24 4.5c-7.607.038-13.06 6.49-12.083 16.413");
}

.xj9silbon {
  cx: 21.752px;
  cy: 12.853px;
  r: 0.75px;
  stroke-miterlimit: 10;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yydv0xbga {
  d: path("M14.685 26.378c-1.7 8.31 1.402 15.544 9.314 15.544s11.013-7.231 9.316-15.54");
}

</style>
