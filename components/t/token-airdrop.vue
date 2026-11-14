<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a63kygbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:token-airdrop" /></template>
<style>
.a63kygbti {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 10q.001-3.457 2.907-5.878Q8.002 1.753 12 1.753t6.843 2.369q2.905 2.42 2.907 5.877V10q0 .167-.071.318t-.199.258l-5.388 4.49q.658 1.081.658 2.434q0 1.968-1.391 3.359T12 22.25t-3.359-1.391T7.25 17.5q0-1.353.658-2.434l-5.388-4.49q-.128-.107-.199-.258T2.25 10m12.874 3.92l3.804-3.17H5.072l3.804 3.17q1.32-1.17 3.124-1.17t3.124 1.17M12 19.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T12 15.5t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v2.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014");
}

</style>
