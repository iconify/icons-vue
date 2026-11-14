<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yap45c86j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:molecule-search" /></template>
<style>
.yap45c86j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 2.25Q6.25 2.25 6.25 6q0 2.008 1.075 2.941l-1.234 1.92Q5.601 10.75 5 10.75q-3.25 0-3.25 3.25T5 17.25T8.25 14q0-1.634-.821-2.446L8.68 9.607q.589.143 1.32.143q3.211 0 3.673-2.75h2.098Q16.01 9.75 19 9.75q3.25 0 3.25-3.25T19 3.25q-2.704 0-3.158 2.25h-2.11Q13.491 2.25 10 2.25m7.5 12.25q-3 0-3 3t3 3q.97 0 1.626-.313l1.344 1.343q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-1.343-1.344q.313-.656.313-1.626q0-3-3-3m0 4.5Q16 19 16 17.5t1.5-1.5t1.5 1.5t-1.5 1.5");
}

</style>
