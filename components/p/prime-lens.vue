<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6o--ebih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:prime-lens" /></template>
<style>
.h6o--ebih {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m6.5 0q0 2.626 2.468 3.524q.069.025.142.036q.073.012.147.008q.074-.003.145-.02q.072-.018.139-.049t.126-.075q.06-.044.11-.098t.088-.118t.064-.133t.036-.142q.012-.073.008-.147q-.003-.074-.02-.145q-.018-.072-.049-.139t-.075-.126t-.098-.11t-.118-.088q-.063-.039-.133-.064Q9.75 13.575 9.75 12q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T9 11.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T8.25 12");
}

</style>
