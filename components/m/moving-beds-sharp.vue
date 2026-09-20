<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjjuoebps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:moving-beds-sharp" /></template>
<style>
.bjjuoebps {
  fill: currentColor;
  d: path("M3.23 21V3h11v18zm1-9.206q.393-.39.903-.592T6.23 11h5q.588 0 1.098.202t.902.592V4h-9zm3.435-3.228Q7.23 8.133 7.23 7.5t.434-1.066Q8.098 6 8.73 6t1.066.434t.434 1.066t-.434 1.066T8.731 9t-1.066-.434M19 14.788l-.708-.688l1.595-1.6H16v-1h3.887l-1.595-1.6l.708-.689L21.788 12zM8.23 18.5h1v-2h2v-1h-2v-2h-1v2h-2v1h2z");
}

</style>
