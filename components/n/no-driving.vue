<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9ea6ccov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:no-driving" /></template>
<style>
.f9ea6ccov {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.03 2.97l17 17q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-17-17q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 3.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094M2.25 12q0-.074.015-.146t.042-.141q.029-.068.07-.129t.093-.114q.052-.052.114-.093q.061-.041.129-.069t.141-.043t.146-.014h4.81q-.06.363-.06.75t.06.75H3q-.074 0-.146-.014q-.073-.015-.141-.043t-.129-.069t-.114-.093t-.093-.114t-.07-.129q-.028-.068-.042-.141t-.015-.146z");
}

</style>
