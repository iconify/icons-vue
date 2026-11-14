<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-eorbbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:stopwatch-stop" /></template>
<style>
.x-eorbbgp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 3.25v1.027q3.247.242 5.614 2.609Q21 9.522 21 13.25t-2.636 6.364T12 22.25t-6.364-2.636T3 13.25t2.636-6.364q2.367-2.367 5.614-2.609V3.25H9.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T8.75 2.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014h5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043q-.072.014-.146.014zm-2.25 6q-1.036 0-1.768.732T8 11.75v3q0 2.5 2.5 2.5h3q2.5 0 2.5-2.5v-3q0-2.5-2.5-2.5z");
}

</style>
