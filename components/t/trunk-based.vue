<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jr5pfrb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:trunk-based" /></template>
<style>
.jr5pfrb9t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 16.349V21.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-9.651l-3.9-3.284Q6.643 9 5.5 9q-3 0-3-3q0-1.5.75-2.25T5.5 3q3 0 3 3q0 .803-.215 1.391l2.965 2.497V2.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v11.888l2.965-2.497q-.215-.588-.215-1.391q0-3 3-3t3 3t-3 3q-1.143 0-1.85-.435z");
}

</style>
