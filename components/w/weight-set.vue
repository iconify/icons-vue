<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwaikab0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:weight-set" /></template>
<style>
.fwaikab0i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.25 4.25q1.036 0 1.768.732T9.75 6.75v4.5h4.5v-4.5q0-2.5 2.5-2.5q1.036 0 1.768.732t.732 1.768v4.5h2.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-2.25v4.5q0 1.036-.732 1.768t-1.768.732q-2.5 0-2.5-2.5v-4.5h-4.5v4.5q0 1.036-.732 1.768t-1.768.732q-2.5 0-2.5-2.5v-4.5H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 12.074 1.75 12t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h2.25v-4.5q0-2.5 2.5-2.5");
}

</style>
