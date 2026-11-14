<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnwjtxg6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ophthalmoscope" /></template>
<style>
.nnwjtxg6a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.75 6.5q0-2.175 1.538-3.712Q9.825 1.25 12 1.25t3.712 1.538Q17.25 4.325 17.25 6.5t-1.538 3.712q-.939.94-2.116 1.305q1.654.665 1.654 2.983v1q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v-1q0-2.318 1.654-2.983q-1.177-.365-2.116-1.305Q6.75 8.675 6.75 6.5m2 9q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h5q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V19q0 1.346-.952 2.298T12 22.25t-2.298-.952T8.75 19zM12 4.5q-2 0-2 2t2 2t2-2t-2-2");
}

</style>
