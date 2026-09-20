<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pel-djvlb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-camera-outline-sharp" /></template>
<style>
.pel-djvlb {
  fill: currentColor;
  d: path("M7 17.808V21V3zm5.588-11.722q.22-.222.22-.549t-.222-.548t-.549-.22t-.548.222t-.22.549t.222.547t.549.22t.548-.22m4.489 11.72h1V22H6V2h12.077v4.192h-1V3H7v18h10.077zm-3.77-2.384v-5.98h2.135l.866-.866H18l.857.865H21v5.981zm4.902-1.945q.445-.445.445-1.058q0-.612-.445-1.045t-1.055-.433t-1.055.433t-.445 1.045t.445 1.058t1.055.445t1.055-.445");
}

</style>
