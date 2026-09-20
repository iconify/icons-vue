<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6m2orbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:water-pump-rounded" /></template>
<style>
.q6m2orbkk {
  fill: currentColor;
  d: path("M13.413 14.413Q14 13.825 14 13q0-.575-.238-1.137t-.912-1.613l-.425-.625Q12.275 9.4 12 9.4t-.425.225l-.425.625q-.675 1.05-.913 1.613T10 13q0 .825.588 1.413T12 15t1.413-.587m-5.838 2.012Q5.75 14.6 5.75 12t1.825-4.425T12 5.75t4.425 1.825T18.25 12t-1.825 4.425T12 18.25t-4.425-1.825M21 11h-1.325q-.25-1.95-1.4-3.55T15.325 5H21q0-.425.288-.713T22 4t.713.288T23 5v6q0 .425-.288.713T22 12q-.4 0-.562-.363T21 11M1 19v-6q0-.425.288-.712T2 12t.713.288T3 13h1.325q.25 1.95 1.4 3.55T8.675 19H3q0 .425-.288.713T2 20t-.712-.288T1 19");
}

</style>
