<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9cgwvacr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:test-watch" /></template>
<style>
.y9cgwvacr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2.25h12q1.76 0 3.005 1.245T22.25 6.5v7q0 1.76-1.245 3.005T18 17.75h-5.25v2.5h2.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-7q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T7.75 21q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h2.75v-2.5H6q-1.76 0-3.005-1.245T1.75 13.5v-7q0-1.76 1.245-3.005T6 2.25m6 3.5q-4.325 0-6.643 3.864q-.053.088-.08.186t-.027.2t.027.2t.08.186Q7.675 14.25 12 14.25t6.643-3.864q.053-.088.08-.186t.027-.2t-.027-.2t-.08-.186Q16.325 5.75 12 5.75");
}

</style>
