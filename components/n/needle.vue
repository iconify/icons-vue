<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufcmu9bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:needle" /></template>
<style>
.ufcmu9bwe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m19.071 4.576l.353.353q.733.732.733 1.767q0 1.036-.733 1.768l-1.059 1.061q-.383.383-.849.566l.317.318q.106.105.163.243t.057.287t-.057.287t-.163.243q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094l-1.591-1.59l-9.37 9.369q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113l9.369-9.37l-1.59-1.591q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.105-.106.243-.163t.287-.057t.287.057t.243.163l.318.317q.183-.465.566-.848l1.061-1.061q.732-.732 1.768-.732q1.035 0 1.767.733");
}

</style>
