<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rgr2-10cm"/><path class="h8mhk5bcy"/><path class="z2l1g7b-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:podcast-episode-x" /></template>
<style>
.h8mhk5bcy {
  d: path("M6.25 13q-.117-.188-.216-.386q-.1-.198-.182-.404t-.144-.418q-.064-.213-.108-.43t-.069-.437t-.03-.442q-.005-.221.01-.442q.014-.222.048-.441q.034-.218.087-.434q.053-.215.125-.424q.072-.21.162-.412t.198-.396t.233-.377t.264-.355q.141-.171.295-.33q.155-.158.323-.302q.169-.145.349-.273t.371-.241t.391-.208t.408-.171q.208-.077.422-.135t.432-.098q.218-.039.439-.058q.22-.02.442-.02t.442.02t.439.058t.432.098q.214.058.422.135q.207.076.408.171t.391.208t.371.241t.349.273q.135.115.262.241q.126.125.244.259t.225.276t.205.291q.097.15.183.305q.087.156.162.318t.138.328q.064.167.115.337q.051.171.09.345t.066.35t.041.354q.014.177.015.355q.001.179-.01.356q-.012.178-.036.355q-.024.176-.06.351q-.037.174-.085.345");
}

.rgr2-10cm {
  d: path("M8.5 10.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z2l1g7b-i {
  d: path("M3 13.25a8 8 0 1 1 15 0m-7.5 2.25v6m5-6l5 5m0-5l-5 5");
}

</style>
