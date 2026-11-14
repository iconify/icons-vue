<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k45go5blw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:medical-id" /></template>
<style>
.k45go5blw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.875 1.75h4.25q2.123 0 3.624 1.501t1.501 3.624v10.25q0 2.123-1.501 3.624t-3.624 1.501h-4.25q-2.123 0-3.624-1.501T4.75 17.125V6.875q0-2.123 1.501-3.624T9.875 1.75m3 5h-1.75q-3.375 0-3.375 3.375v2.25q0 3.375 3.375 3.375h1.75q3.375 0 3.375-3.375v-2.25q0-3.375-3.375-3.375m.625 11h-3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h3q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
