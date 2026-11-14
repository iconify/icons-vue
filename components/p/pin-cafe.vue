<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0pe8qb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-cafe" /></template>
<style>
.j0pe8qb9l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.895 12.943l4.995 6.993q.072.102.174.174q.06.043.128.074q.067.03.139.047q.072.016.146.019q.073.002.146-.01t.142-.038q.069-.027.132-.066t.117-.089q.053-.051.096-.111l4.995-6.993q1.619-2.163 1.364-4.854q-.256-2.695-2.259-4.517T9.5 1.75T4.79 3.572T2.531 8.089q-.255 2.691 1.364 4.854M19.5 16.25h-4.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T14 17v2.5q0 3 3 3h.25q1.732 0 2.464-1H20q2.25 0 2.25-2.25q0-2.121-2-2.243V17q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014m-4 1.5h3.25v1.75q0 1.5-1.5 1.5H17q-1.5 0-1.5-1.5zm5.25 1.5q0 .625-.521.729q.021-.229.021-.479v-.975q.5.113.5.725");
}

</style>
