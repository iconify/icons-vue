<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn3gs_bku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-off-outline-sharp" /></template>
<style>
.hn3gs_bku {
  fill: currentColor;
  d: path("M20.846 22.204L1.392 2.75l.708-.708l19.454 19.454zM18 15.065l-1-1V3H6V2h12v4.83h.923v3.686H18zm-5.412-8.979q.22-.222.22-.549t-.222-.547t-.549-.22t-.548.22t-.22.55t.222.547t.549.22t.548-.22M6 22V5.942l1 1V21h10v-4.058l1 1V22zm7.689-11.277");
}

</style>
