<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5sl2jvni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:wastewater" /></template>
<style>
.n5sl2jvni {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.97 1.97q.105-.106.243-.163t.287-.057t.287.057t.243.163Q18.25 9.189 18.25 14q0 3.21-2.27 5.48t-5.48 2.27t-5.48-2.27T2.75 14q0-4.811 7.22-12.03M18.5 12.5q0-1.75 1.75-1.75T22 12.5t-1.75 1.75t-1.75-1.75M5.97 14.47q-.106.105-.163.243T5.75 15t.057.287t.163.243q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.906-.905 1.47-.905t1.47.905q2.53 2.531 5.06 0q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-1.47 1.469-2.94 0q-2.53-2.531-5.06 0m13.78 1.03Q18 15.5 18 17.25T19.75 19t1.75-1.75t-1.75-1.75m-4 5.25q0-1.75 1.75-1.75t1.75 1.75t-1.75 1.75t-1.75-1.75");
}

</style>
