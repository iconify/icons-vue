<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kv4ev3tbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:send-circle" /></template>
<style>
.kv4ev3tbo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m13.355-2.045L16.28 8.78q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094l-1.175 1.175q-.826-.441-1.823-.041L9.529 9.931q-.904.361-.944 1.333q-.041.972.83 1.407l1.053.526q.223.112.335.335l.526 1.053q.435.871 1.407.83q.972-.04 1.333-.944l1.077-2.692q.4-.998-.041-1.824");
}

</style>
