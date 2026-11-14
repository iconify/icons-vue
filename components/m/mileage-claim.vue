<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ht6d6ra4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mileage-claim" /></template>
<style>
.ht6d6ra4k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 12.5v-3q0-.932.659-1.591T4.5 7.25h1.084l2.28-3.647q.051-.081.12-.147t.152-.112t.176-.07t.188-.024h6q.087 0 .172.02t.163.059q.079.039.146.095t.119.126l2.775 3.7H19.5q2.25 0 2.25 2.25v3q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-.392Q19.856 13 19 13h-2q-2.071 0-3.536 1.464q-.846.847-1.203 1.896q-.511-.675-.511-1.86q0-.719.188-1.25H9.562q.188.531.188 1.25q0 2.75-2.75 2.75T4.25 14.5q0-.719.188-1.25H3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141q-.014-.072-.014-.146M17 14.25q-3.75 0-3.75 3.75T17 21.75h2q3.75 0 3.75-3.75T19 14.25zM14.75 18q0-2.25 2.25-2.25T19.25 18T17 20.25T14.75 18m6.5 0q0 1.371-.835 1.906q.335-.785.335-1.906t-.335-1.906q.835.535.835 1.906");
}

</style>
