<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3r2ffbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:red-blood-cell" /></template>
<style>
.l3r2ffbgr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-3.183 3.098-5.384Q7.826 4.5 12 4.5t7.152 2.116Q22.25 8.817 22.25 12t-3.098 5.384Q16.174 19.5 12 19.5t-7.152-2.116Q1.75 15.183 1.75 12M12 8.25q-5.25 0-5.25 2.75T12 13.75T17.25 11T12 8.25m0 9q-3.861 0-6.506-2.314q-.056-.049-.12-.086t-.134-.06t-.143-.034q-.073-.009-.147-.004t-.145.024t-.137.052q-.067.032-.125.077q-.059.046-.107.101q-.099.112-.146.254q-.048.141-.038.29t.076.282t.178.232Q7.575 18.75 12 18.75q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T12 17.25");
}

</style>
