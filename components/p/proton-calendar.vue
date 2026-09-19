<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVG1X1xceCc" class="gaxcp0emj"/></defs><use href="#SVG1X1xceCc" class="c-zrgpb5l"/><use href="#SVG1X1xceCc" class="c-zrgpb5l"/><path class="c371pgv4h"/><path class="kc_8f-bsm"/><path class="grd-ag25e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:proton-calendar" /></template>
<style>
.c-zrgpb5l {
  stroke-linecap: round;
  stroke-linejoin: round;
}

.c371pgv4h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.207 25.793V15.82a3.14 3.14 0 0 0-3.138-3.138H4.5m17.707 27.456V38.26a4.04 4.04 0 0 1 .964-2.617l7.105-8.338v.005m8.242 3.095l1.759-.957m0 0v7.035m-5.235-3.517a1.76 1.76 0 0 0 1.759-1.758h0a1.76 1.76 0 0 0-1.759-1.758");
}

.gaxcp0emj {
  fill: none;
  stroke: currentColor;
  d: path("M8.535 7.862A4.035 4.035 0 0 0 4.5 11.897v24.206a4.035 4.035 0 0 0 4.035 4.035h20.62v-9.862a4.483 4.483 0 0 1 4.483-4.483H43.5V11.897a4.035 4.035 0 0 0-4.035-4.035Z");
}

.grd-ag25e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.155 40.138h10.31a4.035 4.035 0 0 0 4.035-4.035v-10.31");
}

.kc_8f-bsm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.042 36.483a1.76 1.76 0 0 0 1.759-1.758h0a1.76 1.76 0 0 0-1.759-1.759m-2.663 2.924a2.95 2.95 0 0 0 2.17.594h.493m-2.664-6.448a2.95 2.95 0 0 1 2.173-.588l.492.002m-1.332 3.516h1.331");
}

</style>
