<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o27nu9bhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:query-result" /></template>
<style>
.o27nu9bhy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.125 2.75H6.875q-2.123 0-3.624 1.501T1.75 7.875V8q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h19q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 8.074 1.75 8v8.125q0 2.123 1.501 3.624t3.624 1.501h10.25q2.123 0 3.624-1.501t1.501-3.624v-8.25q0-2.123-1.501-3.624T17.125 2.75m-.875 7.5q1.036 0 1.768.732t.732 1.768v3q0 1.036-.732 1.768t-1.768.732h-8.5q-2.5 0-2.5-2.5v-3q0-2.5 2.5-2.5z");
}

</style>
