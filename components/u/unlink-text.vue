<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbqsuebvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:unlink-text" /></template>
<style>
.wbqsuebvg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m16.263 3.142l-2.121 2.121q-2.297 2.297 0 4.595t4.595 0l2.121-2.121q2.297-2.298 0-4.595t-4.595 0M12.75 14v-4q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T12 9.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v4q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146m-9.608 2.263l2.121-2.121q2.298-2.297 4.595 0t0 4.595l-2.121 2.121q-2.298 2.297-4.595 0t0-4.595");
}

</style>
