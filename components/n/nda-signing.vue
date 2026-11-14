<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm5wk9b8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:nda-signing" /></template>
<style>
.bm5wk9b8v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 11.625q0-2.43-1.75-3.111V7q0-2.75-2.75-2.75T4 7v1.514q-1.75.681-1.75 3.111v1.25q0 1.398.989 2.386q.988.989 2.386.989h2.25q3.375 0 3.375-3.375zM5.625 8.25l-.125.001V7q0-1.25 1.25-1.25T8 7v1.251l-.125-.001zm15.574 3.478q1.124-1.948-.824-3.074q-1.948-1.124-3.073.824l-3.685 6.38q-.286.498-.3 1.071l-.029 1.182q-.013.514.221.889H3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T3 20.5h11q.073 0 .144-.014q.072-.014.139-.042q.068-.027.129-.067t.113-.091t.093-.111t.07-.127t.045-.138t.017-.144q.491.052.977-.246l1.012-.616q.49-.3.775-.796z");
}

</style>
