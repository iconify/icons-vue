<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="jd-ywwefk"/><path class="vsvoqhb-a"/><path class="hke-j7bxq"/><path class="cjk5pzb3o"/><path class="i81wjju_r"/><path class="h5xgpdbhm"/><path class="g_rbnkbip"/><circle class="edjjytbsp"/><circle class="kyc12tvda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:old-woman-medium-dark-skin-tone" /></template>
<style>
.cjk5pzb3o {
  fill: var(--svg-color--df1f32, #df1f32);
  d: path("M18 31.651c-2.519 0-3.494-.753-3.664-.903a1 1 0 0 1 1.293-1.525c.06.039.7.429 2.371.429c1.751 0 2.37-.428 2.376-.433c.414-.367 1.026-.311 1.392.101c.367.413.31 1.062-.103 1.429c-.171.149-1.146.902-3.665.902");
}

.edjjytbsp {
  cx: 32px;
  cy: 24px;
  r: 1px;
  fill: var(--svg-color--aa8dd8, #aa8dd8);
}

.g_rbnkbip {
  fill: var(--svg-color--808285, #808285);
  d: path("M33 12c-2-7-8-9-11.188-9C20 3 18 4 18 4s-2-1-4-1c-3 0-9 2-11 9c-1.648 5.769 2 11 2 11c0-3.001 2-9 7-9s6-4 6-4s.786 4 5.786 4S31 20 31 23c0 0 3.648-5.231 2-11");
}

.h5xgpdbhm {
  fill: var(--svg-color--60352a, #60352a);
  d: path("M23 24a1 1 0 0 1-1-1v-2a1 1 0 1 1 2 0v2a1 1 0 0 1-1 1m-10 0a1 1 0 0 1-1-1v-2a1 1 0 1 1 2 0v2a1 1 0 0 1-1 1");
}

.hke-j7bxq {
  fill: var(--svg-color--808285, #808285);
  d: path("M25 19h-3a1 1 0 1 1 0-2h3a1 1 0 1 1 0 2m-11 0h-3a1 1 0 0 1 0-2h3a1 1 0 0 1 0 2");
}

.i81wjju_r {
  fill: var(--svg-color--915a34, #915a34);
  d: path("M19 28h-2a1 1 0 1 1 0-2h2a1 1 0 1 1 0 2");
}

.jd-ywwefk {
  fill: var(--svg-color--6d6e71, #6d6e71);
  d: path("M13.062 4c0-2.209 2.211-4 4.938-4c2.728 0 4.938 1.791 4.938 4S20.728 8 18 8c-2.727-.001-4.938-1.792-4.938-4");
}

.kyc12tvda {
  cx: 4px;
  cy: 24px;
  r: 1px;
  fill: var(--svg-color--aa8dd8, #aa8dd8);
}

.vsvoqhb-a {
  fill: var(--svg-color--af7e57, #af7e57);
  d: path("M33 21c0-2.14-1.053-3.872-2.373-3.98C29.255 9.555 24.13 4 18 4S6.745 9.555 5.373 17.02C4.053 17.128 3 18.86 3 21c0 2.153 1.066 3.896 2.399 3.983C6.807 31.946 11.906 36 18 36s11.193-4.054 12.602-11.017C31.934 24.896 33 23.153 33 21");
}

</style>
