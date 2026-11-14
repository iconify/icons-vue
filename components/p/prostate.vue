<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_z843bvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:prostate" /></template>
<style>
.o_z843bvb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.25 14q0-2.621-1.617-4.572l4.117-4.117V8.5q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-5q0-.149-.057-.287t-.163-.243q-.105-.106-.243-.163T20.5 2.75h-5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h3.189l-4.117 4.117Q12.621 6.75 10 6.75q-3.003 0-5.127 2.123T2.75 14t2.123 5.127T10 21.25t5.127-2.123Q17.25 17.003 17.25 14m-10.5 0q0-3.25 3.25-3.25T13.25 14T10 17.25T6.75 14");
}

</style>
