<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pezs0kumg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:signal-cellular-connected-no-internet-0-bar-rounded" /></template>
<style>
.pezs0kumg {
  fill: currentColor;
  d: path("M4.373 19.627L19.627 4.373q.379-.379.876-.171t.497.742v1.787q0 .212-.144.356t-.357.144t-.356-.144T20 6.731V5.42L5.421 20H17q.213 0 .356.144t.144.357t-.144.356T17 21H4.944q-.534 0-.742-.497t.171-.876m15.607 1.394q-.21-.21-.21-.52t.21-.521q.209-.21.52-.21t.52.21q.21.209.21.52t-.21.52q-.209.21-.52.21t-.52-.21m.02-3.75v-7.154q0-.213.144-.357t.357-.143t.356.143t.143.357v7.153q0 .213-.144.357t-.357.143t-.356-.143t-.143-.357");
}

</style>
