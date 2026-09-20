<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqt1bebil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:roller-skating" /></template>
<style>
.sqt1bebil {
  fill: currentColor;
  d: path("M4 16V1h8v3H9.5q-.2 0-.35.15T9 4.5t.15.35t.35.15H12v.5q0 .125.013.25t.037.25H9.5q-.2 0-.35.15T9 6.5t.15.35t.35.15h2.9q.35.575.888.975t1.187.6L17.1 9.3q1.3.35 2.1 1.412t.8 2.413V16zm-1.125 6.125Q2 21.25 2 20t.875-2.125T5 17t2.125.875T8 20t-.875 2.125T5 23t-2.125-.875M19 23q-1.25 0-2.125-.875T16 20t.875-2.125T19 17t2.125.875T22 20t-.875 2.125T19 23m-7 0q-1.25 0-2.125-.875T9 20t.875-2.125T12 17t2.125.875T15 20t-.875 2.125T12 23");
}

</style>
