<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nr_t79bla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:opacity-outline" /></template>
<style>
.nr_t79bla {
  fill: currentColor;
  d: path("M6.338 18.7Q4 16.4 4 13.1q0-1.625.625-3.037T6.35 7.55L12 2l5.65 5.55q1.1 1.1 1.725 2.513T20 13.1q0 3.3-2.337 5.6T12 21t-5.663-2.3M6.05 14H17.9q.3-1.8-.337-3.075T16.25 9L12 4.8L7.75 9q-.675.65-1.325 1.925T6.05 14");
}

</style>
