<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o033bnbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:transition-slide-rounded" /></template>
<style>
.o033bnbpk {
  fill: currentColor;
  d: path("M3 20q-.825 0-1.412-.587T1 18V6q0-.825.588-1.412T3 4h2q.825 0 1.413.588T7 6v12q0 .825-.587 1.413T5 20zm8 0q-.825 0-1.412-.587T9 18V6q0-.825.588-1.412T11 4h10q.825 0 1.413.588T23 6v12q0 .825-.587 1.413T21 20z");
}

</style>
