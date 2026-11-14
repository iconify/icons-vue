<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3ce0bb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mesh-node-offline" /></template>
<style>
.r3ce0bb8r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75Q8.75 1.75 8.75 5q0 1.779.974 2.585l-3.831 7.237Q5.482 14.75 5 14.75q-3.25 0-3.25 3.25T5 21.25q2.85 0 3.201-2.5h6.591q.354 3 3.708 3q3.75 0 3.75-3.75t-3.75-3.75q-.47 0-.882.059l-3.356-6.713q.988-.804.988-2.596q0-3.25-3.25-3.25m4.184 13.046q-1.189.734-1.392 2.454H8.201q-.17-1.21-.925-1.835l3.831-7.237q.411.072.893.072q.473 0 .877-.069zm.846 5.734q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141T15.75 20t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113l4-4q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243t.057.287t-.057.287t-.163.243z");
}

</style>
