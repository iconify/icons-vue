<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqmg7ubkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:organic-chemistry" /></template>
<style>
.dqmg7ubkm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 6.102q.187.072.375.18l5 2.885q1.125.65 1.125 1.949v5.768q0 1.299-1.125 1.949l-5 2.885q-1.125.649-2.25 0l-5-2.885q-1.125-.65-1.125-1.949v-5.768q0-1.299 1.125-1.949l5-2.885q.188-.108.375-.18V2.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146zM7.5 14q0 1.864 1.318 3.182T12 18.5t3.182-1.318T16.5 14t-1.318-3.182T12 9.5t-3.182 1.318T7.5 14");
}

</style>
