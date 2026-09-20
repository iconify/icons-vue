<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt-czmoqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:trolley" /></template>
<style>
.wt-czmoqt {
  fill: currentColor;
  d: path("M4 17V5H2V3h4v12h15v2zm2 5q-.825 0-1.412-.587T4 20t.588-1.412T6 18t1.413.588T8 20t-.587 1.413T6 22m1-8V8h6v6zm7 0V8h6v6zm3.588 7.413Q17 20.825 17 20t.588-1.412T19 18t1.413.588T21 20t-.587 1.413T19 22t-1.412-.587");
}

</style>
