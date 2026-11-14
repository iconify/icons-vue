<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhcnuebze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-beer" /></template>
<style>
.jhcnuebze {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.895 12.943l4.995 6.993q.072.102.174.174q.06.043.128.074q.067.03.139.047q.072.016.146.019q.073.002.146-.01t.142-.038q.069-.027.132-.066t.117-.089q.053-.051.096-.111l2.924-4.093q.22-2.006 1.854-2.596l.217-.304q1.619-2.163 1.364-4.854q-.256-2.695-2.259-4.517T9.5 1.75T4.79 3.572T2.531 8.089q-.255 2.691 1.364 4.854M18.25 14.25H16.5q-2.25 0-2.25 2.25v3.75q0 2.25 2.25 2.25h1.75q2.121 0 2.243-2H21.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V16.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-1.076q-.337-1.5-2.174-1.5m0 1.5q.75 0 .75.75v3.75q0 .75-.75.75H16.5q-.75 0-.75-.75V16.5q0-.75.75-.75zm2.5 3.25h-.25v-1.75h.25z");
}

</style>
