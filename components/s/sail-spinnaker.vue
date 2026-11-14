<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mymf_bbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sail-spinnaker" /></template>
<style>
.mymf_bbcd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.785 2.282h-.001q-.057.017-.111.043t-.103.061t-.093.076t-.079.09t-.063.102t-.047.11t-.028.117q-.01.059-.01.119v14.75H4q-.132 0-.255.045q-.124.045-.225.129q-.057.047-.103.105q-.047.057-.081.122q-.034.066-.055.137t-.028.144q-.007.074.001.147q.008.074.03.144q.022.071.057.136q.036.064.083.121l2.5 3q.107.128.258.199t.318.071h11q.167 0 .318-.071t.258-.199l2.5-3q.084-.101.129-.225q.045-.123.045-.255q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T20 17.75H8.75v-3.094Q10.848 16.25 13 16.25q8.75 0 8.75-6.75q0-5.005-5.108-6.951q-4.295-1.636-8.857-.267m.965 1.287q3.79-.977 7.358.382Q20.25 5.529 20.25 9.5q0 5.25-7.25 5.25q-2.084 0-4.25-2.066z");
}

</style>
