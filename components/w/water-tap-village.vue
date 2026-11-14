<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gq27qd2-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:water-tap-village" /></template>
<style>
.gq27qd2-a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.5 1.75q2.75 0 2.75 2.75v.25h4.25q3.75 0 3.75 3.75v2q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-2q0-2.25-2.25-2.25h-4.25V19.5q0 2.75-2.75 2.75T4.75 19.5v-15q0-2.75 2.75-2.75m9.424 11.77q.043-.053.096-.096q.057-.047.121-.083q.065-.035.136-.057q.07-.022.144-.03t.147-.001t.144.028t.137.055q.065.034.122.081q.058.046.105.103q2.674 3.208 2.674 5.23q0 3.25-3.25 3.25t-3.25-3.25q0-2.022 2.674-5.23");
}

</style>
