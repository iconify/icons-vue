<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="ig8-m3hzx"/><path class="ffkbv6bma"/><path class="hdxpysbbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:triangle-left-filled-circle" /></template>
<style>
.ffkbv6bma {
  d: path("M17.5 6.365a1 1 0 0 1 1.5.866V18.77a1 1 0 0 1-1.5.866l-9.999-5.769a1 1 0 0 1 0-1.732zM12.003 13L16 15.306v-4.612z");
}

.hdxpysbbn {
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.ig8-m3hzx {
  d: path("M7.501 13.866a1 1 0 0 1 0-1.732l10-5.769A1 1 0 0 1 19 7.231V18.77a1 1 0 0 1-1.5.866z");
}

.n1lsf0bnc {
  fill: currentColor;
  fill-rule: evenodd;
}

</style>
