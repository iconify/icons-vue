<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh5kbqk3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:supermarket-nearby" /></template>
<style>
.sh5kbqk3b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.5 2.25h2q.063 0 .126.011q.062.01.122.031t.115.052t.105.07t.092.087t.075.1q.034.054.058.113q.024.058.038.12l.666 2.927q.641-.511 1.527-.511h10.902q1.197 0 1.947.933q.75.932.495 2.101l-.984 4.5q-.43 1.966-2.443 1.966H8.409q-.542 0-.969-.142q-.124.089-.274.123q-.145.033-.292.008t-.274-.104t-.212-.202q-.086-.121-.119-.267L3.901 3.75H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 3.074 1.75 3t.014-.146t.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m6 13.5q-2.25 0-2.25 2.25t2.25 2.25T10.75 18T8.5 15.75M14.25 18q0-2.25 2.25-2.25T18.75 18t-2.25 2.25T14.25 18");
}

</style>
