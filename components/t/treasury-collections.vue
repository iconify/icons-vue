<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ai1wh5onn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:treasury-collections" /></template>
<style>
.ai1wh5onn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.464 3.464Q7 4.929 7 7t1.464 3.536T12 12t3.536-1.464Q17 9.071 17 7t-1.464-3.536Q14.071 2 12 2T8.464 3.464M2.5 13.25h5q.097 0 .191.025q.094.024.179.072t.154.116t.119.151l1.282 2.136h5.15l1.282-2.136q.05-.083.119-.151q.07-.068.154-.116q.085-.048.179-.072q.094-.025.191-.025h5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v5.5q0 2.75-2.75 2.75h-15q-2.75 0-2.75-2.75V14q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014");
}

</style>
