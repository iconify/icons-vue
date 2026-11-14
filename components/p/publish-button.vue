<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwdht8bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:publish-button" /></template>
<style>
.vwdht8bsm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.887 4.053L9.47 13.47q-.053.052-.094.113t-.069.13q-.028.068-.043.141T9.25 14q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l9.417-9.417q.43.81.055 1.791l-4.215 11.025q-.5 1.307-1.893 1.437t-2.126-1.062l-2.22-3.607q-.093-.152-.245-.245l-3.607-2.22q-1.192-.733-1.062-2.126t1.437-1.893l11.025-4.214v-.001q.981-.375 1.791.055");
}

</style>
