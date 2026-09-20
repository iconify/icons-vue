<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdbt80b1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:media-output-outline-sharp" /></template>
<style>
.xdbt80b1q {
  fill: currentColor;
  d: path("M2 20V2h13v6.05q-.525.05-1.025.188T13 8.575V4H4v14h4v2zm6-3.025V16q0-.275.013-.537t.062-.538Q7.6 14.8 7.3 14.4t-.3-.9q0-.625.438-1.062T8.5 12q.125 0 .25.025T9 12.1q.25-.45.563-.862t.662-.788q-.375-.225-.812-.337T8.5 10q-1.45 0-2.475 1.025T5 13.5q0 1.35.863 2.313T8 16.975m1.563-8.912Q10 7.625 10 7t-.437-1.062T8.5 5.5t-1.062.438T7 7t.438 1.063T8.5 8.5t1.063-.437M14 22h-4v-6q0-2.5 1.75-4.25T16 10t4.25 1.75T22 16v6h-4v-5h2.5v-1q0-1.875-1.312-3.187T16 11.5t-3.187 1.313T11.5 16v1H14z");
}

</style>
