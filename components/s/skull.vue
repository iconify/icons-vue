<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aa24k302c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:skull" /></template>
<style>
.aa24k302c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.881 5.059Q4.75 7.415 4.75 11q0 3.2 2.5 4.91v2.59q0 2.75 2.75 2.75h4q2.75 0 2.75-2.75v-2.59q2.5-1.71 2.5-4.91q0-3.585-2.131-5.941Q15.029 2.75 12 2.75T6.881 5.059M12 21.25q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V17q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v3.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014M7.25 11q0-2 2-2q.828 0 1.414.586T11.25 11t-.586 1.414T9.25 13q-2 0-2-2m7.5-2q2 0 2 2t-2 2t-2-2t2-2");
}

</style>
