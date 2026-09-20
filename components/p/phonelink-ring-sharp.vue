<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fa8i94b5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:phonelink-ring-sharp" /></template>
<style>
.fa8i94b5x {
  fill: currentColor;
  d: path("M18.35 14.85L16.9 13.4q.3-.275.463-.637t.162-.763t-.162-.763t-.463-.637l1.45-1.45q.575.575.875 1.313t.3 1.537t-.3 1.538t-.875 1.312m2.45 2.45l-1.4-1.4q.775-.775 1.2-1.775T21.025 12T20.6 9.875T19.4 8.1l1.4-1.4q1.075 1.05 1.65 2.425T23.025 12t-.575 2.875T20.8 17.3M5 23V1h14v6h-2V6H7v12h10v-1h2v6z");
}

</style>
