<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhxysdqtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:warehouse" /></template>
<style>
.uhxysdqtb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 9v12q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h5.5q-2.25 0-2.25-2.25v-6q0-2.25 2.25-2.25h7q2.25 0 2.25 2.25v6q0 2.25-2.25 2.25H21q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V9q0-.096-.024-.19q-.025-.093-.072-.177t-.114-.153t-.149-.12l-9-5.5q-.088-.054-.188-.082q-.099-.028-.203-.028t-.203.028t-.188.082l-9 5.5q-.082.05-.149.12t-.114.153t-.072.177q-.024.094-.024.19");
}

</style>
