<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x03xhlbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-off-sharp" /></template>
<style>
.x03xhlbbr {
  fill: currentColor;
  d: path("M20.846 22.204L1.392 2.75l.708-.708l19.454 19.454zM12.588 6.086q.22-.222.22-.549t-.222-.547t-.549-.22t-.548.22t-.22.55t.222.547t.549.22t.548-.22M6 22V5.942l12 12V22zm12-6.934L6.029 2.832V2H18v4.83h.923v3.686H18z");
}

</style>
