<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqo_y5brp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:skew-left" /></template>
<style>
.cqo_y5brp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.5 19.75q4.988 0 7.799-7.018Q13.205 4.75 17 4.75q2.116 0 4.179 10.506q.679 3.458 1.052 5.075q.016.072.019.146t-.01.147q-.012.073-.039.142q-.026.069-.065.131q-.039.063-.09.117t-.111.097t-.127.073t-.139.047q-.072.016-.146.019t-.147-.01q-.073-.012-.142-.039q-.069-.026-.132-.065q-.062-.039-.116-.09t-.097-.111t-.073-.127t-.047-.139q-.379-1.642-1.062-5.124Q17.882 6.25 17 6.25q-2.747 0-5.295 7.006l-.009.023Q8.508 21.25 2.5 21.25q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014");
}

</style>
