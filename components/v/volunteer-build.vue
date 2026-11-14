<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-60oub2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:volunteer-build" /></template>
<style>
.a-60oub2d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.935 8.643L8.81 3.632q2.19-1.866 4.38 0l5.875 5.011q1.185 1.011 1.185 2.568v2.547l-.543-.543q-2.121-2.121-4.242 0t0 4.242l.125.125l-2.254 2.254q-.186.186-.318.414H5.125q-3.375 0-3.375-3.375v-5.664q0-1.557 1.185-2.568m15.888 5.456l2.828 2.828q1.237 1.237 0 2.474t-2.474 0l-.759-.758l-3.138 3.137q-.105.106-.243.163T14.75 22t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141T14 21.25t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113l3.137-3.138l-1.008-1.009q-1.237-1.237 0-2.474t2.474 0m-1.06 1.06q-.177-.176-.354 0q-.176.177 0 .354l2.828 2.828q.177.176.354 0q.176-.177 0-.354z");
}

</style>
