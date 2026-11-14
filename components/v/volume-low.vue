<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smp9e0bhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:volume-low" /></template>
<style>
.smp9e0bhm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.828 8.25H5.25q-2.5 0-2.5 2.5v2.5q0 1.036.732 1.768t1.768.732h1.578q.384 0 .669.256l2.001 1.802q1.085.976 2.418.382q1.333-.593 1.334-2.053V7.863q-.001-1.46-1.334-2.053q-1.333-.594-2.418.383l-2.001 1.8q-.285.257-.669.257M16.75 12q0-1.761-1.245-3.005q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.805.806.805 1.945t-.805 1.945q-.053.052-.094.113t-.069.13q-.028.068-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069q.068.028.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094Q16.75 13.761 16.75 12");
}

</style>
