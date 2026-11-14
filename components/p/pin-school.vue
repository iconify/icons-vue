<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6zm6-bul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-school" /></template>
<style>
.x6zm6-bul {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.564 22.61Q2.25 15.957 2.25 11q.001-4.038 2.857-6.892Q7.962 1.253 12 1.253t6.893 2.855Q21.749 6.962 21.75 11q0 4.957-9.314 11.61q-.047.034-.1.06q-.052.026-.107.044q-.056.018-.113.027q-.058.009-.116.009t-.116-.009t-.113-.027t-.107-.044t-.1-.06M12.75 8.636v-.792q.338.015.692-.133l.346-.144q.879-.365.879-1.317t-.879-1.317l-.345-.144h-.001q-.396-.166-.772-.127q-.047-.093-.118-.169t-.159-.132q-.088-.054-.189-.083q-.1-.028-.204-.028q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T11.25 5v3.636q-.221.087-.442.225l-2.501 1.562q-1.057.661-1.057 1.908v2.419Q7.25 17 9.5 17h5q2.25 0 2.25-2.25v-2.419q0-1.247-1.058-1.908l-2.499-1.562q-.222-.138-.443-.225");
}

</style>
