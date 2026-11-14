<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-sci-b-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sap-drop" /></template>
<style>
.b-sci-b-b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.75 2.25H4.25q-2.5 0-2.5 2.5t2.5 2.5h6.891q-.358 1.347-1.887 3.468Q6.75 14.191 6.75 16.5q0 2.175 1.538 3.712Q9.825 21.75 12 21.75t3.712-1.538q1.538-1.537 1.538-3.712q0-2.309-2.504-5.782q-1.529-2.121-1.887-3.468h6.891q1.036 0 1.768-.732t.732-1.768t-.732-1.768t-1.768-.732m-9.24 14q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-.01q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T9.75 17t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
