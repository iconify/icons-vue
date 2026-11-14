<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_x_z6btp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:rest-api" /></template>
<style>
.t_x_z6btp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.5 9.75q-3.25 0-3.25-3.25q0-3.029 2.824-3.235q1.401-2.085 4.014-1.892q2.577.191 3.661 2.4q2.501.238 2.501 2.977q0 3-3 3h-2.5v1.689l.97-.969q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141T15 11t-.014.146q-.015.073-.043.141t-.069.13t-.094.113l-2.25 2.25q-.105.106-.243.163T12 14q-.034 0-.067-.003q-.132-.012-.251-.068t-.212-.149l-2.25-2.25q-.053-.052-.094-.113t-.069-.13t-.043-.141T9 11t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094l.97.969V9.75zm3.5 5.5q-5.75 0-5.75 2v3q0 2 5.75 2t5.75-2v-3q0-2-5.75-2m-4.25 5v-1.479q1.437.479 4.25.479t4.25-.479v1.479q0 .5-4.25.5t-4.25-.5");
}

</style>
