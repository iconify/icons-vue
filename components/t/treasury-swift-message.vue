<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u29b7zb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:treasury-swift-message" /></template>
<style>
.u29b7zb2a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.818 3.318Q16.136 2 18 2t3.182 1.318T22.5 6.5t-1.318 3.182T18 11t-3.182-1.318T13.5 6.5t1.318-3.182m6.128 2.432q-.326-2.106-2.623-2.241q-.704.856-.848 2.241zm-4.978 0q.091-1.088.455-1.959q-1.146.518-1.369 1.959zM6 4.75h6.506q-.256.822-.256 1.75q0 2.129 1.345 3.7l-2.6 1.878l-8.062-5.691q-.095-.067-.206-.102q.126-.148.268-.29Q4.24 4.75 6 4.75m10.423 4.459q-.364-.871-.455-1.959h-.914q.223 1.441 1.369 1.959m4.523-1.959h-3.471q.144 1.385.848 2.241q2.297-.135 2.623-2.241m-2.946 5q-1.848 0-3.276-1.014l-3.285 2.372q-.047.034-.099.061t-.107.044t-.113.027t-.116.01t-.116-.008t-.113-.027q-.056-.017-.108-.043t-.1-.059l-8.5-6q-.04-.029-.076-.062Q1.75 8.225 1.75 9v7q0 1.76 1.245 3.005T6 20.25h12q1.76 0 3.005-1.245T22.25 16v-5.626q-.089.097-.184.192Q20.382 12.25 18 12.25");
}

</style>
