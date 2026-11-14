<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-p1zbcnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:vaccine-vial" /></template>
<style>
.g-p1zbcnw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.25 1.75h-2.5q-2.5 0-2.5 2.5q0 .621.154 1.087q-1.654.38-1.654 2.413q0 1.521.926 2.117q-.219.178-.425.384q-1.501 1.501-1.501 3.624v3.25q0 2.123 1.501 3.624t3.624 1.501h2.25q2.123 0 3.624-1.501t1.501-3.624v-3.25q0-2.123-1.501-3.624q-.206-.206-.425-.384q.926-.596.926-2.117q0-2.081-1.732-2.43q.232-.487.232-1.07q0-1.036-.732-1.768T13.25 1.75m1.5 12q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-5.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T8.5 14.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
