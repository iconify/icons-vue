<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wg3xl7_bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:progress-steps" /></template>
<style>
.wg3xl7_bz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-2.75 2.75-2.75q2.345 0 2.69 2h2.12q.345-2 2.69-2t2.69 2h2.12q.345-2 2.69-2q2.75 0 2.75 2.75t-2.75 2.75q-2.345 0-2.69-2h-2.12q-.345 2-2.69 2t-2.69-2H7.19q-.345 2-2.69 2q-2.75 0-2.75-2.75");
}

</style>
