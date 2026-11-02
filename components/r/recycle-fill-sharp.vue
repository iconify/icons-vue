<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="meox7rb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:recycle-fill-sharp" /></template>
<style>
.meox7rb7v {
  fill: currentColor;
  d: path("m9.634 5.098l1.5-2.598a1.002 1.002 0 0 1 1.732 0l3.853 6.674l.473-1.766a1 1 0 0 1 1.932.517l-1.098 4.098a.997.997 0 0 1-1.225.708l-4.098-1.099a1 1 0 1 1 .518-1.931l1.766.473L12 5l-.634 1.098a1 1 0 0 1-1.732-1M6.34 19h-3a1 1 0 0 1-.866-1.5l3.853-6.674l-1.766.473a1 1 0 1 1-.518-1.931L8.14 8.27l.001-.001a1 1 0 0 1 1.225.708l1.098 4.098a1 1 0 0 1-.705 1.224a1 1 0 0 1-1.227-.707l-.473-1.766L5.072 17H6.34a1 1 0 0 1 0 2m7.907-3.293L12.954 17h5.974l-.634-1.098a1 1 0 0 1 1.732-1l1.5 2.598a.998.998 0 0 1-.866 1.5h-7.706l1.293 1.293a1 1 0 0 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414");
}

</style>
