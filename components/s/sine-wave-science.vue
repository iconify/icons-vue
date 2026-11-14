<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlnefrbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sine-wave-science" /></template>
<style>
.mlnefrbyb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.25 4.875q-3.436 0-5.47 6.913q-.03.104-.03.212v.004q0 .06.01.119t.029.116t.047.111t.065.101t.079.09q.043.041.093.075q.049.035.103.061q.055.026.112.043q.104.03.212.03h8.944q2.006 6.375 5.306 6.375q3.436 0 5.47-6.913q.03-.104.03-.212v-.004q0-.06-.01-.119t-.029-.116t-.047-.111t-.065-.101t-.079-.09t-.093-.075q-.049-.035-.103-.061q-.055-.026-.112-.043q-.104-.03-.212-.03h-8.944Q10.55 4.875 7.25 4.875m5.77 7.875h7.46q-1.615 4.875-3.73 4.875t-3.73-4.875m-2.04-1.5H3.52q1.615-4.875 3.73-4.875t3.73 4.875");
}

</style>
