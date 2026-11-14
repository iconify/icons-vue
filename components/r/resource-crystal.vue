<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxjkx1b_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:resource-crystal" /></template>
<style>
.nxjkx1b_i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m17.514 6.499l-4-3.637q-1.514-1.376-3.028 0l-4 3.637q-.736.67-.736 1.665v8.125q0 1.066.825 1.741l4 3.273q1.425 1.167 2.85 0l4-3.273q.825-.675.825-1.741V8.164q0-.995-.736-1.665M12.75 17.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-11q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T12 5.75t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146z");
}

</style>
