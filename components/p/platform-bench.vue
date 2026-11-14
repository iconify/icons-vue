<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ene0bgbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:platform-bench" /></template>
<style>
.ene0bgbqc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 2.75h12.5q1.036 0 1.768.732t.732 1.768q0 2.5-2.5 2.5v2h1q1.036 0 1.768.732t.732 1.768q0 2.5-2.5 2.5h-1v3.5h3.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T1.75 19t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h3.25v-3.5h-1q-2.5 0-2.5-2.5t2.5-2.5h1v-2q-2.5 0-2.5-2.5q0-1.036.732-1.768T5.75 2.75m11 7v-2h-9.5v2zm0 5v3.5h-9.5v-3.5z");
}

</style>
