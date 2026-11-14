<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z662mouvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sports-merch" /></template>
<style>
.z662mouvk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.25 7.25h.819q3.125 0 3.365 3.117l.597 7.749q.113 1.471-.889 2.553t-2.477 1.081H6.335q-1.474 0-2.477-1.081q-1.002-1.082-.889-2.552l.597-7.751q.24-3.116 3.365-3.116h.819V6.5q0-1.76 1.245-3.005T12 2.25t3.005 1.245T16.25 6.5zm-7 0V6.5q0-2.75 2.75-2.75q1.139 0 1.945.805q.805.806.805 1.945v.75zm10.5 3.5H4.25q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069q.068.028.141.043t.146.014h15.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
