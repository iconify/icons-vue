<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVG8Ictd5YF" x1="8.59%" x2="77.471%" y1="1.954%" y2="73.896%"><stop offset="0%" class="obc-cjbvy"/><stop offset="100%" class="icrvf5b4s"/></linearGradient><path id="SVGNVTtUC0X" class="i5demccvd"/></defs><mask id="SVGc6EHndOq" class="n1mjunbsu"><use href="#SVGNVTtUC0X"/></mask><use href="#SVGNVTtUC0X" class="r956-2oif"/><path mask="url(#SVGc6EHndOq)" class="v0vxx6npl"/><path fill="url(#SVG8Ictd5YF)" mask="url(#SVGc6EHndOq)" class="m0pmdxb2m"/><path mask="url(#SVGc6EHndOq)" class="n3abn83vw"/><path mask="url(#SVGc6EHndOq)" class="e14xs1cyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:pushbullet" /></template>
<style>
.e14xs1cyo {
  fill: var(--svg-color--fff, #fff);
  d: path("M121.041 189.6c-5.699 0-8.508-2.809-8.508-8.508V72.774c0-5.698 2.809-8.507 8.508-8.507h37.537c32.178 0 52.628 32.273 52.628 63.025S190.578 189.6 158.578 189.6z");
}

.i5demccvd {
  d: path("M256 128c0 70.692-57.308 128-128 128S0 198.692 0 128S57.308 0 128 0s128 57.308 128 128");
}

.icrvf5b4s {
  stop-color: var(--svg-color--3ea16f, #3ea16f);
}

.m0pmdxb2m {
  d: path("M63.111 187.022L96.178 72l64.533 60.978L200 90.133l87.533 86.289l-110.844 124.889z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.n3abn83vw {
  fill: var(--svg-color--fff, #fff);
  d: path("M77 189.6c-16.733 0-16.733 0-16.733-16.733V81c0-16.733 0-16.733 16.733-16.733h3.334c16.733 0 16.733 0 16.733 16.733v91.867c0 16.733 0 16.733-16.733 16.733z");
}

.obc-cjbvy {
  stop-color: var(--svg-color--4cb36b, #4cb36b);
}

.r956-2oif {
  fill: var(--svg-color--67bf79, #67bf79);
}

.v0vxx6npl {
  fill: var(--svg-color--67bf79, #67bf79);
  d: path("M256 128c0 70.692-57.308 128-128 128S0 198.692 0 128S57.308 0 128 0s128 57.308 128 128");
}

</style>
