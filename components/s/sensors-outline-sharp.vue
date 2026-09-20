<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o10g49cvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sensors-outline-sharp" /></template>
<style>
.o10g49cvn {
  fill: currentColor;
  d: path("M5.637 18.364q-1.235-1.241-1.936-2.87T3 12q0-1.87.701-3.499t1.936-2.864l.713.713q-1.1 1.1-1.725 2.55T4 12q0 1.675.625 3.125T6.35 17.65zm2.825-2.826q-.685-.69-1.073-1.595T7 12q0-1.044.389-1.949t1.072-1.59l.714.714q-.55.55-.862 1.275T8 12t.313 1.55t.862 1.275zm2.837-2.837Q11 12.402 11 12t.299-.701T12 11t.701.299T13 12t-.299.701T12 13t-.701-.299m4.24 2.838l-.714-.714q.55-.55.863-1.275T16 12t-.312-1.55t-.863-1.275l.714-.714q.684.685 1.072 1.59T17 12q0 1.039-.388 1.943t-1.073 1.596m2.824 2.825l-.713-.714q1.1-1.1 1.725-2.55T20 12q0-1.656-.625-3.106T17.65 6.35l.714-.713Q19.598 6.87 20.299 8.5T21 12q0 1.864-.701 3.493t-1.936 2.87");
}

</style>
