<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osi01ybmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-camera-sharp" /></template>
<style>
.osi01ybmn {
  fill: currentColor;
  d: path("M6 22V2h12.077v4.192h-2.748l-.885.866h-3.521v10.75h7.154V22zm7.308-6.577v-5.98h2.134l.866-.866H18l.857.865H21v5.981zm4.9-1.945q.446-.445.446-1.058q0-.612-.445-1.045t-1.055-.433t-1.055.433t-.445 1.045t.445 1.058t1.055.445t1.055-.445m-5.621-7.392q.22-.222.22-.549t-.222-.547t-.549-.22t-.548.22t-.22.55t.222.547t.549.22t.548-.22");
}

</style>
