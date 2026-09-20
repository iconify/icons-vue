<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="x988-cchn"/><path class="ovc9o_blj"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rlb-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ovc9o_blj {
  fill: var(--svg-color--fff, #fff);
  d: path("m12.077 7.083l.108.009q.41.037 0 .024l-.508.004c-.306.01-.602.014-.907.014l-.471.01h-.075c-.118 0-.217 0-.33.09a6.15 6.15 0 0 0-1.656 2.022c-.018.033-.06.07-.103.075l-2.193.283l.001.005l.004.004h.005q.902.102 1.802.217q.093.011.188.009l.01.01a.02.02 0 0 1 0 .018a6.1 6.1 0 0 0 0 4.253v.01l-.005.004q-1 .132-2 .259l.005.01l2.197.258a.1.1 0 0 1 .07.052a6.1 6.1 0 0 0 1.708 2.07a.27.27 0 0 0 .155.066l2.278.037a8 8 0 0 1-.668.047l-.142.02l-.113.013l-.197.015c-.386.028-.772.056-1.153.094l-5.283.498l-.226.024c-.16.019-.343.042-.513.047a.1.1 0 0 0-.051.019q-.031.02.004.019h.226c.268 0 .536.014.8.032l.419.024q3.792.151 7.584.33l.277.018c.212.014.423.028.64.014h.028a6.22 6.22 0 0 0 4.088-1.698A6.07 6.07 0 0 0 20 11.933a6.07 6.07 0 0 0-3.472-5.42a6.4 6.4 0 0 0-3.077-.62q-1.226.064-2.451.112c-.165.01-.325.024-.48.02l-.612.027q-.675.038-1.35.061q-1.888.094-3.778.175q-.395.022-.743.023c-.038 0-.047.01-.014.033l.038.01q.246.002.494.032l.329.033q2.548.249 5.095.504q.563.054 1.19.094c.104 0 .202.01.306.023l.32.024l.282.023zm4.032 4.92a2.306 2.306 0 0 1-2.324 2.287a2.306 2.306 0 0 1-2.324-2.286a2.303 2.303 0 0 1 2.324-2.292a2.304 2.304 0 0 1 2.324 2.292");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.x988-cchn {
  fill: var(--svg-color--ffa101, #ffa101);
  d: path("M24 0H0v24h24z");
}

</style>
