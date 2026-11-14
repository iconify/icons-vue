<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hylyphb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ski-goggles" /></template>
<style>
.hylyphb5a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 7.75H4q-2.25 0-2.25 2.25v4q0 3.75 4.25 3.75h2.5q.084 0 .167-.019q.082-.018.158-.055t.142-.089q.066-.053.119-.118l1.774-2.219h2.28l1.774 2.219q.053.065.119.118t.142.089t.158.055q.083.019.167.019H18q4.25 0 4.25-3.75v-4q0-2.25-2.25-2.25m-2 3q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
