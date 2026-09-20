<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fol2q7bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-object-track-rounded" /></template>
<style>
.fol2q7bgp {
  fill: currentColor;
  d: path("M7.904 19Q6.7 19 5.85 18.15T5 16.098t.85-2.054t2.054-.852h10.192q1.203 0 2.054.85t.85 2.052t-.85 2.054t-2.054.852zm-2-8.192q-1.203 0-2.053-.85Q3 9.108 3 7.906t.85-2.054T5.905 5h10.192q1.203 0 2.054.85T19 7.902t-.85 2.054t-2.054.852z");
}

</style>
