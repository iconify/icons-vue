<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi-7uoblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-phone" /></template>
<style>
.pi-7uoblg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 9V8q0-5.25 9.75-5.25T21.75 8v1q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043T21 9.75h-4.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T15.75 9v-.75h-7.5V9q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q2.25 9.074 2.25 9m16.093 4.181Q17.518 11 15.187 11H8.813q-2.331 0-3.156 2.181l-1.513 4q-.627 1.655.379 3.112T7.3 21.75h9.4q1.771 0 2.777-1.457t.379-3.112zM9.5 16.5Q9.5 14 12 14q1.036 0 1.768.732T14.5 16.5t-.732 1.768T12 19q-2.5 0-2.5-2.5");
}

</style>
