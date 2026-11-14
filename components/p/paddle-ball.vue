<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nypk7sbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:paddle-ball" /></template>
<style>
.nypk7sbbj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 7.5q0-1.968 1.391-3.359T6.5 2.75t3.359 1.391T11.25 7.5q0 1.581-.899 2.791L12 11.939l1.649-1.648q-.899-1.21-.899-2.791q0-1.968 1.391-3.359T17.5 2.75t3.359 1.391T22.25 7.5t-1.391 3.359T17.5 12.25q-1.581 0-2.791-.899L13.061 13l4.469 4.47q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094L12 14.061L7.53 18.53q-.105.106-.243.163T7 18.75t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141T6.25 18q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113L10.939 13l-1.648-1.649q-1.21.899-2.791.899q-1.968 0-3.359-1.391T1.75 7.5m7.5 12.25Q9.25 17 12 17t2.75 2.75T12 22.5t-2.75-2.75");
}

</style>
