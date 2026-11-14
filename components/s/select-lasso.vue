<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sykkd75et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:select-lasso" /></template>
<style>
.sykkd75et {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.082 4.481Q3.25 6.314 3.25 9t2.832 4.519q.086.056.174.11q-1.042 1.191-.942 2.793q.146 2.335 2.539 2.813l.024.005q.498.083.498.479q0 .63-.791 1.157q-.061.041-.114.093q-.052.052-.093.114q-.041.061-.07.129q-.028.068-.042.141t-.015.146t.014.147q.015.072.043.14t.069.13t.093.114t.114.093t.129.07q.068.028.141.042t.146.015q.074 0 .147-.014q.072-.015.14-.043t.13-.069q1.459-.973 1.459-2.405q0-1.661-1.738-1.957q-1.252-.255-1.326-1.434q-.071-1.14.841-1.981q2.146.903 4.848.903q3.742 0 6.418-1.731Q21.75 11.686 21.75 9t-2.832-4.519Q16.242 2.75 12.5 2.75T6.082 4.481");
}

</style>
