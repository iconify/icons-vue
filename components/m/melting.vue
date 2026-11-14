<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xszpubcuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:melting" /></template>
<style>
.xszpubcuu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 1.75h10q2.75 0 2.75 2.75v5q0 2.75-2.75 2.75h-4.25v1.25q0 2.25-2.25 2.25T8.25 13.5v-1.25H7q-2.75 0-2.75-2.75v-5q0-2.75 2.75-2.75m9.01 12.5H16q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141q.014-.072.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014M5.837 17.778q-3.086.635-3.087 1.971v.002q.001 1.336 3.087 1.971q2.565.529 6.163.529t6.163-.529q3.089-.636 3.087-1.973q.002-1.335-3.087-1.971q-2.565-.529-6.163-.529t-6.163.529");
}

</style>
