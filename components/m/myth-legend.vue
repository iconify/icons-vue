<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqvqhcbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:myth-legend" /></template>
<style>
.wqvqhcbya {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 3.25q2.622 0 2.744 2.5h9.512q.122-2.5 2.744-2.5q2.75 0 2.75 2.75v12q0 2.75-2.75 2.75q-2.622 0-2.744-2.5H7.244q-.122 2.5-2.744 2.5q-2.75 0-2.75-2.75V6q0-1.139.805-1.945q.806-.805 1.945-.805m2.75 13.5h9.5v-9.5h-9.5zm7.25-5.5h-5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T8.75 12t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h5q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
