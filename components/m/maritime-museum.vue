<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uso1vbcxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:maritime-museum" /></template>
<style>
.uso1vbcxe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.808 8.364l6.749-4.765q1.442-1.017 2.883 0l6.751 4.765q1.058.747 1.058 2.043v8.343q0 2.5-2.5 2.5H5.25q-2.5 0-2.5-2.5v-8.343q0-1.296 1.058-2.043M11.25 14H6.5q-.218 0-.403.117q-.126.08-.211.203q-.086.122-.118.267q-.033.146-.007.293t.106.273l1.75 2.75q.051.079.12.144t.152.11t.175.069t.186.024h7.5q.095 0 .186-.024q.092-.023.175-.069q.083-.045.152-.11t.12-.144l1.75-2.75q.117-.185.117-.403q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T17.5 14h-4.75v-1.25H16q.162 0 .31-.067t.254-.189q.099-.112.146-.254q.048-.141.038-.29t-.076-.282t-.178-.232l-4-3.5q-.103-.09-.23-.138q-.128-.048-.264-.048q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146zm2.754-2.75H12.75v-1.097z");
}

</style>
