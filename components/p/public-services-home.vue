<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="gcmifebju"/><path class="hmtwgw9fv"/><path class="e7kyngbxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:public-services-home" /></template>
<style>
.e7kyngbxo {
  d: path("M33.347 13.583v18.548a2.21 2.21 0 0 1-2.213 2.213H17.036a2.21 2.21 0 0 1-2.213-2.213v-6.14");
}

.gcmifebju {
  d: path("M42.5 34.681c-1.454 2.518-6.049 5.07-8.567 6.524S26.907 45.362 24 45.362s-7.415-2.703-9.933-4.157s-7.113-4.006-8.567-6.524S4.133 26.907 4.133 24S4.046 15.837 5.5 13.319s6.049-5.07 8.567-6.524S21.093 2.638 24 2.638s7.415 2.703 9.933 4.157s7.113 4.006 8.567 6.524S43.867 21.093 43.867 24s.087 8.163-1.367 10.681");
}

.hmtwgw9fv {
  d: path("M36.684 23.876L24 13.172L11.317 23.876");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
