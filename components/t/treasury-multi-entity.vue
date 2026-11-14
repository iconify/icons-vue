<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddc5tgblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:treasury-multi-entity" /></template>
<style>
.ddc5tgblq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.25 1.75h-4.5q-2.5 0-2.5 2.5v1.5q0 1.036.732 1.768t1.768.732h1.5v2h-6.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T4 11v2.757q-2.25.121-2.25 2.493v2q0 2.5 2.5 2.5h1q2.5 0 2.5-2.5v-2q0-2.372-2.25-2.493V11.75h5.75v2.007Q9 13.878 9 16.25v2q0 2.5 2.5 2.5h1q1.036 0 1.768-.732T15 18.25v-2q0-2.372-2.25-2.493V11.75h5.75v2.007q-2.25.121-2.25 2.493v2q0 2.5 2.5 2.5h1q1.036 0 1.768-.732t.732-1.768v-2q0-2.372-2.25-2.493V11q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-6.5v-2h1.5q1.036 0 1.768-.732t.732-1.768v-1.5q0-2.5-2.5-2.5");
}

</style>
