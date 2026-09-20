<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtpzacc4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pin-invoke-outline-sharp" /></template>
<style>
.mtpzacc4d {
  fill: currentColor;
  d: path("M2 20V4h12v2H4v12h16v-6h2v8zm8.05-3.625l-1.4-1.425L11.6 12H9.35v-2H15v5.65h-2v-2.225zM19 10q-1.25 0-2.125-.875T16 7t.875-2.125T19 4t2.125.875T22 7t-.875 2.125T19 10");
}

</style>
