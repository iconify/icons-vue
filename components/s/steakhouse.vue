<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u87f0nb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:steakhouse" /></template>
<style>
.u87f0nb-b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.376 13.166Q2.539 10.41 3.94 7.258Q5.428 3.91 9.41 3.505q2.315-.323 5.292 1.317q1.824 1.005 2.921 1.188q2.59.432 3.28 2.641q.657 2.1-.873 3.629Q17.311 15 9 15q-3.25 0-4.6-1.8zM6.5 9q0 2.5 2.5 2.5q1.036 0 1.768-.732T11.5 9t-.732-1.768T9 6.5Q6.5 6.5 6.5 9m15 7.5h-19q-.122 0-.237.038q-.142.048-.254.145q-.113.098-.18.232q-.067.133-.077.282q-.011.149.036.29Q3.043 21.25 12 21.25t10.212-3.763q.038-.115.038-.237q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
