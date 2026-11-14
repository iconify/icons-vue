<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0h4m5byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:normal-vector" /></template>
<style>
.t0h4m5byl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m8.22 6.72l3.249-3.25h.001q.105-.106.243-.163T12 3.25t.287.057t.243.163h.001l3.249 3.25q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.105.106-.243.163T15.25 8t-.287-.057t-.243-.163l-1.97-1.969v8.439h4.9q1.338 0 1.926 1.202t-.234 2.259l-1.3 1.671q-.676.868-1.776.868H6.35q-1.338 0-1.926-1.202t.234-2.259l1.3-1.671q.676-.868 1.776-.868h3.516V5.811L9.28 7.78q-.105.106-.243.163T8.75 8t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141T8 7.25t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113");
}

</style>
