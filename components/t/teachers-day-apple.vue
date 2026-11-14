<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awl4labcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:teachers-day-apple" /></template>
<style>
.awl4labcv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.536 2.976q1.84-1.438 5.127-.708q.145.032.267.118t.203.211q.08.126.106.273t-.007.293q-.02.09-.061.172q-1.401 2.802-5.421 2.298v1.394q1.845-.945 4.443-.252Q21.25 7.857 21.25 12.5q0 4.083-2.488 7.045Q16.489 22.25 14 22.25q-.696 0-1.461-.342q-.351-.158-.539-.158t-.539.158q-.765.342-1.461.342q-2.489 0-4.762-2.705Q2.75 16.583 2.75 12.5q0-4.643 4.057-5.725q2.598-.693 4.443.252V3.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014q.151 0 .291.059t.245.167");
}

</style>
