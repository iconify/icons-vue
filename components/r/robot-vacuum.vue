<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krv2g-jbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:robot-vacuum" /></template>
<style>
.krv2g-jbf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.5 12q-.001-3.936 2.781-6.719T12 2.497t6.719 2.784Q21.501 8.064 21.5 12q.001 3.936-2.781 6.719T12 21.503q-3.936 0-6.719-2.784Q2.499 15.936 2.5 12M5 6q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T5 7.5h14q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T19 6zm4.5 6.5Q9.5 15 12 15q1.036 0 1.768-.732T14.5 12.5t-.732-1.768T12 10q-2.5 0-2.5 2.5");
}

</style>
