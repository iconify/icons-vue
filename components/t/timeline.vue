<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ez2xwmbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:timeline" /></template>
<style>
.ez2xwmbck {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.25 2.25h-4.5q-2.5 0-2.5 2.5v.75q0 1.036.732 1.768T4.75 8h4.5q1.036 0 1.768-.732T11.75 5.5v-.75q0-1.036-.732-1.768T9.25 2.25M7 9.25q-2.345 0-2.69 2H2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h1.81q.345 2 2.69 2t2.69-2h4.62q.345 2 2.69 2t2.69-2h1.81q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-1.81q-.345-2-2.69-2t-2.69 2H9.69q-.345-2-2.69-2m5.25 9.25q0-2.5 2.5-2.5h4.5q1.036 0 1.768.732t.732 1.768v.75q0 1.036-.732 1.768t-1.768.732h-4.5q-1.036 0-1.768-.732t-.732-1.768z");
}

</style>
