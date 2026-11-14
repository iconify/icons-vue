<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8ycpxbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sheet-music-folder" /></template>
<style>
.v8ycpxbtt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 7q0-2.75 2.75-2.75h4.5q.149 0 .287.057t.243.163l1.781 1.78H19q2.75 0 2.75 2.75v8q0 2.75-2.75 2.75H5q-2.75 0-2.75-2.75zm10.5 8.5v-3.768l1.803.492q.071.019.145.024q.073.005.147-.004q.073-.009.143-.033q.07-.023.134-.06q.064-.036.12-.085q.056-.048.101-.107t.078-.124t.053-.138q.019-.071.024-.145q.005-.073-.004-.147q-.009-.073-.033-.143q-.023-.07-.06-.134q-.036-.064-.085-.12q-.048-.056-.107-.101t-.124-.078t-.138-.053l-2.75-.75Q12.1 10 12 10q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v2.576q-.337-.076-.75-.076q-2.25 0-2.25 2.25t2.25 2.25t2.25-2.25");
}

</style>
