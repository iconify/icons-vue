<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td_yybb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:workflow-cache" /></template>
<style>
.td_yybb1j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.875 1.75h-1.25q-3.312 0-3.374 3.25H5.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T5 5.75v5.002q-1.317.042-2.261.987q-.989.988-.989 2.386v1.25q0 3.375 3.375 3.375h1.25q3.375 0 3.375-3.375v-1.25q0-3.312-3.25-3.374V6.5h5.751q.062 3.25 3.374 3.25h1.25q3.375 0 3.375-3.375v-1.25q0-3.375-3.375-3.375M18.25 13.5q-4 0-4 2.25V20q0 2.25 4 2.25q1.511 0 2.612-.508Q22.25 21.101 22.25 20v-4.25q0-1.101-1.388-1.742q-1.101-.508-2.612-.508m0 3q-2.5 0-2.5-.75t2.5-.75t2.5.75t-2.5.75m-2.5 3.5v-2.338q.949.338 2.5.338q1.435 0 2.5-.458V20q0 .75-2.5.75t-2.5-.75");
}

</style>
