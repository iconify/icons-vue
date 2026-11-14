<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c31p1kz8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:token-limit" /></template>
<style>
.c31p1kz8q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 20.25q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-15q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T20 3.75t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v2.75H6q-3.25 0-3.25 3.25v3q0 3.25 3.25 3.25h13.25v2.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014m-.75-11.5v6.5H6q-1.75 0-1.75-1.75v-3q0-1.75 1.75-1.75zM7.5 10H16q2 0 2 2t-2 2H7.5q-2 0-2-2t2-2");
}

</style>
