<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oaic_u28w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:trolley-outline-sharp" /></template>
<style>
.oaic_u28w {
  fill: currentColor;
  d: path("M4 17V5H2V3h4v12h15v2zm2 5q-.825 0-1.412-.587T4 20t.588-1.412T6 18t1.413.588T8 20t-.587 1.413T6 22m1-8V8h6v6zm2-2h2v-2H9zm5 2V8h6v6zm2-2h2v-2h-2zm1.588 9.413Q17 20.825 17 20t.588-1.412T19 18t1.413.588T21 20t-.587 1.413T19 22t-1.412-.587M9 12h2zm7 0h2z");
}

</style>
