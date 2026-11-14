<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtj6ftb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:newspaper-seller" /></template>
<style>
.gtj6ftb5c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.318 3.818Q5 5.136 5 7t1.318 3.182T9.5 11.5t3.182-1.318T14 7t-1.318-3.182T9.5 2.5T6.318 3.818M13.75 20q0 2.25 2.25 2.25h4.5q1.75 0 1.75-1.75V15q0-1.75-1.75-1.75H17q-1.75 0-1.75 1.75v.75h-.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146zm-1.263-5.462q.104.035.193.098q.09.062.158.148q.067.085.108.187t.051.21q-.286.325-.411.74q-.134.066-.283.077t-.29-.036Q10.628 15.5 9.5 15.5q-5.75 0-5.75 6q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T3 22.25t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-3.286 2.056-5.398Q6.353 14 9.5 14q1.372 0 2.987.538m4.263 6.212V15q0-.25.25-.25h3.5q.25 0 .25.25v5.5q0 .25-.25.25z");
}

</style>
