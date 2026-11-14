<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6pgp0bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:progress-segments" /></template>
<style>
.q6pgp0bsj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.875 7.25q2.875 0 2.875 2.875v3.75q0 2.875-2.875 2.875T2 13.875v-3.75Q2 7.25 4.875 7.25M15 10.125q0-2.875-2.875-2.875T9.25 10.125v3.75q0 2.875 2.875 2.875T15 13.875zm4.375-2.875q2.875 0 2.875 2.875v3.75q0 2.875-2.875 2.875T16.5 13.875v-3.75q0-2.875 2.875-2.875");
}

</style>
