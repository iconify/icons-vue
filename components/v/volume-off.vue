<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7r88cc2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:volume-off" /></template>
<style>
.p7r88cc2c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.03 2.97l17 17q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-17-17q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 3.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094m9.22 7.452L9.247 6.419l.251-.226q1.085-.977 2.418-.383q1.333.593 1.334 2.053zm0 5.715v-.059L5.422 8.25H5.25q-2.5 0-2.5 2.5v2.5q0 1.036.732 1.768t1.768.732h1.578q.384 0 .669.256l2.001 1.802q1.085.976 2.418.382q1.333-.593 1.334-2.053");
}

</style>
