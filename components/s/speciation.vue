<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3bq-nbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:speciation" /></template>
<style>
.l3bq-nbbx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 2.25Q2.25 2.25 2.25 5T5 7.75q.857 0 1.447-.267q.62.562 1.575 1.328Q11.25 11.4 11.25 14v7.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V14q0-2.6 3.228-5.189q.955-.766 1.575-1.328q.59.267 1.447.267q2.75 0 2.75-2.75T19 2.25T16.25 5q0 .831.251 1.411q-.572.516-1.461 1.23q-2.104 1.687-3.04 3.461q-.936-1.774-3.04-3.461q-.889-.714-1.461-1.23q.251-.58.251-1.411q0-2.75-2.75-2.75");
}

</style>
