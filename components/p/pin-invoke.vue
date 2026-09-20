<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l17jjkb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pin-invoke" /></template>
<style>
.l17jjkb3g {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h10v2H4v12h16v-6h2v6q0 .825-.587 1.413T20 20zm6.05-3.625l-1.4-1.425L11.6 12H9.35v-2H15v5.65h-2v-2.225zM19 10q-1.25 0-2.125-.875T16 7t.875-2.125T19 4t2.125.875T22 7t-.875 2.125T19 10");
}

</style>
