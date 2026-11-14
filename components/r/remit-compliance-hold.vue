<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wh0ss5lvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:remit-compliance-hold" /></template>
<style>
.wh0ss5lvs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.733 17.869q-.093.161-.224.292t-.292.223t-.34.139t-.364.046q-.1 0-.198-.015q-.099-.015-.194-.044t-.186-.07q-.09-.042-.173-.096q-.084-.054-.159-.119q-.075-.066-.14-.141q-.065-.076-.118-.16q-.054-.083-.095-.174l-1.006-2.213q-.119-.261-.315-.471q-.195-.21-.448-.346l-2.924-1.574q-.106-.057-.204-.129q-.098-.071-.184-.155q-.087-.084-.162-.18q-.074-.095-.135-.2q-.06-.104-.106-.216t-.075-.229q-.03-.118-.044-.238t-.01-.241t.023-.24t.056-.235t.088-.224q.052-.11.118-.211t.145-.192q.08-.092.171-.171t.192-.145q.102-.066.211-.118l9.461-4.452q.121-.057.25-.095t.262-.056t.267-.015t.267.026t.259.066t.246.105t.227.141q.109.08.203.175t.175.203q.079.108.141.227t.105.246t.066.259t.026.267q.002.134-.015.267t-.056.262q-.038.129-.095.25l-2.138 4.543M10 15L20.5 3.5m-4 11.75v5.5m3-5.5v5.5");
}

</style>
