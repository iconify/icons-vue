<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="omro_cbox"/><path class="hijt_bc1c"/><path class="sg3l-iq1b"/><path class="f0ibjzb_j"/><path class="sp7xn-bgk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:people" /></template>
<style>
.f0ibjzb_j {
  d: path("M10.05 13.75a2.5 2.5 0 0 0-2.5 2.5v1.5a1 1 0 0 1-2 0v-1.5a4.5 4.5 0 0 1 9 0v1.5a1 1 0 1 1-2 0v-1.5a2.5 2.5 0 0 0-2.5-2.5");
}

.hijt_bc1c {
  d: path("M4.05 11a1.5 1.5 0 0 0-1.5 1.5V14a1 1 0 0 1-2 0v-1.5a3.5 3.5 0 0 1 7 0V14a1 1 0 1 1-2 0v-1.5a1.5 1.5 0 0 0-1.5-1.5M16 8.25a1 1 0 1 1 0-2a1 1 0 0 1 0 2m0 2a3 3 0 1 1 0-6a3 3 0 0 1 0 6");
}

.n1lsf0bnc {
  fill: currentColor;
  fill-rule: evenodd;
}

.omro_cbox {
  d: path("M4 8.25a1 1 0 1 0 0-2a1 1 0 0 0 0 2m0 2a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.sg3l-iq1b {
  d: path("M15.95 11a1.5 1.5 0 0 1 1.5 1.5V14a1 1 0 1 0 2 0v-1.5a3.5 3.5 0 0 0-7 0V14a1 1 0 1 0 2 0v-1.5a1.5 1.5 0 0 1 1.5-1.5");
}

.sp7xn-bgk {
  d: path("M10 11a1 1 0 1 0 0-2a1 1 0 0 0 0 2m0 2a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

</style>
