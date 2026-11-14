<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dry5e1xsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:store-delivery-van" /></template>
<style>
.dry5e1xsg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 7v10q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h1.81q-.06.345-.06.75q0 2.75 2.75 2.75t2.75-2.75q0-.405-.06-.75h4.62q-.06.345-.06.75q0 2.75 2.75 2.75t2.75-2.75q0-.405-.06-.75h1.81q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4q0-.149-.057-.287t-.163-.243l-4-4q-.105-.106-.243-.163T17.5 8.25h-3.25V5.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014H4Q1.75 4.75 1.75 7m17.095 9.25q-.672-.5-1.845-.5t-1.845.5h-.905v-6.5h2.939l3.561 3.561v2.939zM7 15.75q-1.173 0-1.845.5H3.25V7q0-.75.75-.75h8.75v10H8.845q-.672-.5-1.845-.5");
}

</style>
