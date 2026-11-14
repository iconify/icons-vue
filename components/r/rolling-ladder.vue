<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6olewb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:rolling-ladder" /></template>
<style>
.u6olewb6h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.5 2.75h-19q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146t.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h7.449L4.853 19.074Q3.75 19.36 3.75 20.75q0 1.75 1.75 1.75t1.75-1.75q0-1.214-.842-1.586L7.41 16.25h3.914l-.971 2.824Q9.25 19.36 9.25 20.75q0 1.75 1.75 1.75t1.75-1.75q0-1.214-.842-1.586l2.551-7.419l.001-.002l2.575-7.493H21.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014m-6.91 4h-3.914l.859-2.5h3.914zm-1.375 4H9.301l.859-2.5h3.914zm-1.375 4H7.926l.859-2.5h3.914z");
}

</style>
