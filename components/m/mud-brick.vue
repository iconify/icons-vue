<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndkj2fb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mud-brick" /></template>
<style>
.ndkj2fb1l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m1.97 10.469l3.5-3.499q.105-.106.243-.163T6 6.75h15.5q.149 0 .287.057t.243.163l.007.007q.103.105.158.24q.055.136.055.283V14q0 .149-.057.287t-.163.243l-3.5 3.5q-.105.106-.243.163T18 18.25H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V11q0-.149.057-.287t.163-.243zM9.5 13.5H6q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043T6 15h3.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T9.5 13.5");
}

</style>
