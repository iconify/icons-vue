<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-1ep0y2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:molecule-model" /></template>
<style>
.k-1ep0y2p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 2.75q-2.75 0-2.75 2.75T5 8.25q.661 0 1.163-.159l1.84 2.301Q7.25 11.319 7.25 13q0 3.75 3.75 3.75q1.497 0 2.397-.598l1.797 1.648Q15 18.303 15 19q0 2.5 2.5 2.5T20 19t-2.5-2.5q-.742 0-1.264.22l-1.867-1.711q.381-.814.381-2.009q0-1.172-.366-1.977l2.083-1.763q.772.49 2.033.49q1.346 0 2.298-.952T21.75 6.5t-.952-2.298T18.5 3.25q-3.25 0-3.25 3.25q0 .933.268 1.598l-2.091 1.77Q12.522 9.25 11 9.25q-1.023 0-1.766.279L7.358 7.184q.392-.646.392-1.684q0-2.75-2.75-2.75");
}

</style>
