<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olez90kex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:remote-job" /></template>
<style>
.olez90kex {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.125 2.25h7.75q1.398 0 2.386.989q.989.988.989 2.386v3.25q0 3.375-3.375 3.375h-7.75q-3.375 0-3.375-3.375v-3.25q0-1.398.989-2.386q.988-.989 2.386-.989m8.375 11H2q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h11.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014m.25 4.25q0-1.76 1.245-3.005T18 13.25t3.005 1.245T22.25 17.5t-1.245 3.005T18 21.75t-3.005-1.245T13.75 17.5");
}

</style>
