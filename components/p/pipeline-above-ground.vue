<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmpfrubqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pipeline-above-ground" /></template>
<style>
.lmpfrubqc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 5.25h15q2.75 0 2.75 2.75q0 2.512-2.295 2.729l1.632 6.526q.068.008.133.028t.126.052t.115.073t.099.093t.081.11t.06.122t.037.131t.012.136q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T1.75 18q0-.068.012-.136q.013-.067.037-.131t.06-.122q.035-.059.081-.11q.045-.051.099-.093t.115-.073q.061-.032.126-.052t.133-.028l1.632-6.526Q1.75 10.512 1.75 8q0-1.139.805-1.945q.806-.805 1.945-.805m-.539 12h2.078L5 13.092zm3.625 0h1.828l1.625-6.5H5.961zm3.375 0h2.078L12 13.092zm3.625 0h1.828l1.625-6.5h-5.078zm3.375 0h2.078L19 13.092z");
}

</style>
