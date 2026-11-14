<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x07diwwwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pii-redaction" /></template>
<style>
.x07diwwwk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.25 5.75H4.75q-2.5 0-2.5 2.5v1q0 1.036.732 1.768t1.768.732h14.5q1.036 0 1.768-.732t.732-1.768v-1q0-1.036-.732-1.768T19.25 5.75m-15.75 10H15q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H3.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014");
}

</style>
