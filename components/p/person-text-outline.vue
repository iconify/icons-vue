<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m00o7fa1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-text-outline" /></template>
<style>
.m00o7fa1n {
  fill: currentColor;
  d: path("M16.846 16.885v-1H21v1zm-2-4.385v-1H21v1zm-2-4.384v-1H21v1zm-6.192 2.812Q6 10.278 6 9.35t.65-1.582q.649-.654 1.576-.654t1.582.65t.654 1.577t-.65 1.581t-1.577.654t-1.581-.65M3 16.886V15.56q0-.326.164-.621q.163-.296.44-.475q1.048-.598 2.195-.916t2.432-.318t2.432.318t2.195.917q.277.178.44.474q.164.295.164.621v1.323zm3.087-2.356q-1.062.298-2.052.855v.5h8.392v-.5q-.99-.557-2.052-.855q-1.061-.298-2.144-.298t-2.144.298m3.01-4.316q.365-.365.365-.867t-.365-.866t-.866-.364t-.866.364T7 9.346t.365.867t.866.364t.866-.364m-.866 5.672");
}

</style>
