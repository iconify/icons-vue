<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mq-ueub_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-work" /></template>
<style>
.mq-ueub_a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.25 6.25H18q1.76 0 3.005 1.245T22.25 10.5V13q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-19q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146v-2.5q0-1.76 1.245-3.005T6 6.25h1.75V5q0-2.25 2.25-2.25h4q.932 0 1.591.659T16.25 5zM1.75 13q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v4q0 1.76-1.245 3.005T18 21.25H6q-1.76 0-3.005-1.245T1.75 17zm7.5-6.75V5q0-.75.75-.75h4q.75 0 .75.75v1.25z");
}

</style>
