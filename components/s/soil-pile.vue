<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcgamwbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:soil-pile" /></template>
<style>
.tcgamwbec {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m19.468 4.414l-1.249-1q-.117-.093-.26-.134t-.292-.025t-.279.088t-.224.188q-.046.058-.08.124q-.034.065-.054.136q-.021.071-.027.145q-.007.073.002.147q.008.073.03.144t.058.135t.083.121t.105.103l.678.541l-5.87 7.675q-.53-.052-1.089-.052q-6.707 0-9.212 7.513q-.038.115-.038.237q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h17q.122 0 .237-.038q.142-.048.254-.145q.113-.098.18-.232q.067-.133.077-.282q.011-.149-.036-.29q-1.955-5.865-6.471-7.151l5.389-7.047l.651.521q.058.046.124.08q.065.034.136.054q.071.021.145.027q.073.007.147-.002q.073-.008.144-.03t.135-.058t.121-.083t.103-.105t.08-.124t.054-.136t.027-.145q.007-.073-.002-.147q-.008-.073-.03-.144t-.058-.135t-.083-.121t-.105-.103z");
}

</style>
