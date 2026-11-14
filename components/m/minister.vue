<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iuusjo_my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:minister" /></template>
<style>
.iuusjo_my {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 7q0-1.968 1.391-3.359T10.5 2.25t3.359 1.391T15.25 7t-1.391 3.359T10.5 11.75t-3.359-1.391T5.75 7m4.75 6.25q2.469 0 4.358.851q-.045.131-.071.267q-2.537.548-2.537 3.632v1.75q0 .812.3 1.5H4q-1.75 0-1.75-1.75q0-2.798 2.468-4.577q2.32-1.673 5.782-1.673m12 4.75q0-2.5-2.5-2.5v-.75q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T19.25 14h-2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v.75q-2.5 0-2.5 2.5v1.75q0 1.036.732 1.768T16 22.25h4q1.036 0 1.768-.732t.732-1.768zM16 17h4q1 0 1 1v1.75q0 1-1 1h-4q-.414 0-.707-.293T15 19.75V18q0-1 1-1m2.75 2.5q0-.653-.134-1.25H16.25v1.25z");
}

</style>
