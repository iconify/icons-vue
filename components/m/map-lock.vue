<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qah_i0bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:map-lock" /></template>
<style>
.qah_i0bnk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.75 9.81q1.284.214 2.255 1.185Q20.25 12.24 20.25 14v4q0 1.76-1.245 3.005T16 22.25H8q-1.76 0-3.005-1.245T3.75 18v-4q0-1.76 1.245-3.005q.971-.971 2.255-1.185V7q0-1.968 1.391-3.359T12 2.25t3.359 1.391T16.75 7zm-8-.06V7q0-3.25 3.25-3.25T15.25 7v2.75zm4 7.75v-3q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T12 13.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v3q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146");
}

</style>
