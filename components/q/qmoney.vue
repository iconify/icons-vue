<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="qrbcuab9t"/><path class="eidppdb2e"/><path class="ilqkcjbdb"/><path class="g1m4ymrrx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qmoney" /></template>
<style>
.eidppdb2e {
  d: path("m6.931 14.692l26.745-7.58a3.33 3.33 0 0 1 4.12 2.308l5.576 19.758a3.34 3.34 0 0 1-2.303 4.13l-26.745 7.58a3.33 3.33 0 0 1-4.12-2.308L4.628 18.822a3.34 3.34 0 0 1 2.303-4.13");
}

.g1m4ymrrx {
  d: path("M25.06 13.115a10.756 10.756 0 0 1 11.34 7.8h0c1.617 5.728-1.706 11.685-7.422 13.306a10.7 10.7 0 0 1-4.304.318");
}

.ilqkcjbdb {
  d: path("M32.165 20.751c1.663 5.893-1.755 12.02-7.635 13.687h0c-5.88 1.666-11.994-1.76-13.657-7.652h0c-1.662-5.892 1.756-12.02 7.635-13.686h0c5.88-1.667 11.995 1.759 13.657 7.651");
}

.qrbcuab9t {
  d: path("M21.255 23.01c-.302-1.07-1.333-1.709-2.311-1.432c-.979.278-1.524 1.363-1.222 2.433l.851 3.014l7.068-2.003l-.85-3.015c-.302-1.07-1.333-1.708-2.312-1.43s-1.523 1.361-1.221 2.431l.85 3.016zm3.859-.088l1.204-.342M16.72 25.3l1.205-.34");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
