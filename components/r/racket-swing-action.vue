<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpi278bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:racket-swing-action" /></template>
<style>
.cpi278bqt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.242 2.5q-.196.002-.367.1Q5.454 5.152 5.5 10.257q.001.149.06.286q.058.138.164.242q.107.105.245.16q.139.056.288.055q.074-.001.146-.016t.14-.044t.129-.07t.113-.094t.092-.115q.041-.062.068-.13q.028-.069.042-.141q.014-.073.013-.147q-.003-.33.017-.648q.139 2.452 1.442 4.263q.21.291.433.543l-5.731 5.731q-.106.105-.163.243t-.057.287t.057.287t.163.243q.052.053.113.094t.13.069t.141.043q.072.014.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l5.814-5.812q1.005.62 2.215.62q2.248 0 3.791-2.142Q17.5 11.831 17.5 9t-1.459-4.858Q14.498 2 12.25 2q-1.086 0-2.008.5");
}

</style>
