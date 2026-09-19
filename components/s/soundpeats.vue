<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lkyi26bok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:soundpeats" /></template>
<style>
.lkyi26bok {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.11 24.595c2.998 7.536 7.688 13.729 15.876 17.905c8.772-4.474 13.53-11.263 16.491-19.54L7.523 14.425V5.5h32.653v7.035");
}

</style>
