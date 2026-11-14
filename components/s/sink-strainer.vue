<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqqd90b1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sink-strainer" /></template>
<style>
.wqqd90b1e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.399 4.399Q1.25 7.547 1.25 12t3.149 7.601Q7.547 22.75 12 22.75t7.601-3.149Q22.75 16.453 22.75 12t-3.149-7.601Q16.453 1.25 12 1.25T4.399 4.399M9.5 6.5Q9.5 4 12 4q1.036 0 1.768.732T14.5 6.5t-.732 1.768T12 9Q9.5 9 9.5 6.5m-3 3Q9 9.5 9 12t-2.5 2.5T4 12t2.5-2.5m11 0Q20 9.5 20 12t-2.5 2.5T15 12t2.5-2.5m-5.49 1.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H12q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T11.25 12t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014zM9.5 17.5Q9.5 15 12 15q1.036 0 1.768.732T14.5 17.5t-.732 1.768T12 20q-2.5 0-2.5-2.5");
}

</style>
