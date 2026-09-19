<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="aql-10z2m"/><path class="a4kcg-3np"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:retroplayer" /></template>
<style>
.a4kcg-3np {
  d: path("M9.8 31.1h11.3c3.8 0 6.9-3.6 6.9-8.1s-3.1-8.1-6.9-8.1H9.8m4.3 0L25.7 37h0");
}

.aql-10z2m {
  d: path("M42.3 20.7L15.6 5c-1.8-1.1-4.2-.5-5.3 1.4c-.3.6-.5 1.3-.5 2v31.3c0 2.1 1.7 3.9 3.8 3.9c.7 0 1.4-.2 2-.5l26.6-15.6c1.8-1.1 2.5-3.4 1.4-5.3c-.3-.7-.8-1.2-1.3-1.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
