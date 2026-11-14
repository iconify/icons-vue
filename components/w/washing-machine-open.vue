<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztrjpxbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:washing-machine-open" /></template>
<style>
.ztrjpxbrk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 1.75H6q-1.76 0-3.005 1.245T1.75 6v12q0 1.76 1.245 3.005T6 22.25h5q1.76 0 3.005-1.245T15.25 18V6q0-1.76-1.245-3.005T11 1.75M15.25 7q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-12q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 7.074 1.75 7t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h12q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146m1 7q0-5.25 2.75-5.25T21.75 14T19 19.25T16.25 14M8.5 10q1.657 0 2.828 1.172Q12.5 12.343 12.5 14t-1.172 2.828Q10.157 18 8.5 18q-4 0-4-4t4-4");
}

</style>
