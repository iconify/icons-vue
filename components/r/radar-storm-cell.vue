<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eaf_oyb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:radar-storm-cell" /></template>
<style>
.eaf_oyb5d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75q4.112 0 7.057 2.816q-.104-.047-.217-.061t-.225.007t-.214.074t-.181.134l-6.75 6.75q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l6.75-6.75q.106-.105.163-.243t.057-.287q0-.161-.066-.307Q22.25 7.888 22.25 12q0 4.246-3.002 7.248T12 22.25t-7.248-3.002T1.75 12M6 15.5Q6 18 8.5 18t2.5-2.5T8.5 13T6 15.5");
}

</style>
