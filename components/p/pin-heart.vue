<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysbravwfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-heart" /></template>
<style>
.ysbravwfs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.495 19.555Q2.75 14.332 2.75 8.5q0-2.589 1.831-4.419Q6.411 2.25 9 2.25t4.419 1.831T15.25 8.5q0 5.832-5.745 11.055q-.052.047-.111.083t-.124.062t-.132.037q-.069.013-.138.013t-.138-.013q-.068-.012-.132-.037q-.065-.025-.124-.062q-.059-.036-.111-.083M9 5.75q-2.75 0-2.75 2.75T9 11.25t2.75-2.75T9 5.75m8.607 15.889Q14 19.419 14 16.75q0-2.5 2.5-2.5q.89 0 1.5.523q.61-.523 1.5-.523q2.5 0 2.5 2.5q0 2.669-3.607 4.889q-.089.054-.189.083q-.1.028-.204.028t-.204-.028q-.1-.029-.189-.083");
}

</style>
