<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d08niybvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mortar-and-pestle" /></template>
<style>
.d08niybvq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.607 8.559l-4-5.5q-.044-.06-.098-.11t-.117-.089t-.133-.064t-.142-.037t-.147-.008t-.145.02q-.072.017-.139.048t-.127.074q-.06.044-.11.098t-.089.117q-.038.063-.064.133q-.025.069-.037.142t-.008.147t.02.145t.048.139t.074.127l4 5.5q.044.06.098.11t.117.089q.063.038.133.064q.069.025.142.037t.147.008t.145-.02t.139-.048t.127-.074q.06-.044.11-.098t.089-.117q.038-.063.064-.133q.025-.069.037-.142t.008-.147t-.02-.145t-.048-.139t-.074-.127M20 10.25H4q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146q0 3.686 2.532 6.218T12 19.75t6.218-2.532T20.75 11q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T20 10.25");
}

</style>
