<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6yxvkdro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:stock-trolley" /></template>
<style>
.o6yxvkdro {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.815 17.681q-.498.569-1.565.569H3.75q-2 0-2-2q0-.828.586-1.414t1.414-.586h.2q-.2-.459-.2-1v-4.5q0-2.5 2.5-2.5h6q2.5 0 2.5 2.5v4.5q0 .541-.2 1h3.7q.268 0 .5.036V4.25H17.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h4q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-1.25V17q0 .107-.03.21q-.03.104-.088.194t-.139.161t-.178.116M5.5 18.25q2 0 2 2t-2 2t-2-2t2-2m10 0q2 0 2 2t-2 2t-2-2t2-2");
}

</style>
