<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wblol6qqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:phone-vertical-scroll-24-filled" /></template>
<style>
.wblol6qqj {
  fill: currentColor;
  d: path("M15.75 2A2.25 2.25 0 0 1 18 4.25v15.5A2.25 2.25 0 0 1 15.75 22h-7.5A2.25 2.25 0 0 1 6 19.75V4.25A2.25 2.25 0 0 1 8.25 2zm-2.036 11.475L12 15.225l-1.718-1.75a.75.75 0 0 0-1.07 1.05l2.253 2.296c.294.3.777.3 1.07 0l2.25-2.296a.75.75 0 1 0-1.07-1.05m1.072-3.954l-2.25-2.296a.75.75 0 0 0-.987-.075l-.084.075L9.212 9.52a.75.75 0 0 0 .987 1.125l.083-.074L12 8.821l1.714 1.75a.75.75 0 0 0 1.143-.965zl-2.25-2.296z");
}

</style>
