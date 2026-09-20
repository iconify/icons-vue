<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="od0pqabdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:remember-me-outline-sharp" /></template>
<style>
.od0pqabdo {
  fill: currentColor;
  d: path("M6 22V2h12v20zm1-2.5V21h10v-1.5zm0-15h10V3H7zM12 15q-1.35 0-2.625.388T7 16.5v2h10v-2q-1.1-.725-2.375-1.112T12 15m0-1q1.35 0 2.613.343t2.387.972V5.5H7v9.816q1.125-.631 2.388-.974T12 14m1.77-2.228q.73-.729.73-1.77t-.728-1.771t-1.77-.731t-1.771.729T9.5 9.998t.729 1.771t1.769.731t1.771-.728m-2.828-.713Q10.5 10.617 10.5 10t.441-1.059T12 8.5t1.059.441q.441.442.441 1.059t-.441 1.059T12 11.5t-1.059-.441M12 18.5h5H7zm0 1");
}

</style>
