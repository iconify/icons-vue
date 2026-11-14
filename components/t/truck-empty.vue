<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6dmgqztb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:truck-empty" /></template>
<style>
.t6dmgqztb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.875 4.75h-6.75q-3.375 0-3.375 3.375v5.75q0 3.02 2.702 3.338q-.202.543-.202 1.287q0 2.75 2.75 2.75t2.75-2.75q0-.719-.188-1.25h2.313q1.185 0 1.954-.416q.046.094.117.171q.07.078.159.133t.19.083q.1.029.205.029h.438q-.188.531-.188 1.25q0 2.75 2.75 2.75t2.75-2.75q0-.719-.188-1.25H21.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V12q0-.134-.047-.26q-.046-.126-.134-.228l-3-3.5q-.106-.125-.256-.193q-.149-.069-.313-.069h-3.261q-.182-3-3.364-3m5.625 11h-2.625q.375-.75.375-1.875V9.25h2.905l2.595 3.027v3.473z");
}

</style>
