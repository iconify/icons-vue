<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zuozovbmq"/><path class="aaf9dhb8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-voice-fill" /></template>
<style>
.aaf9dhb8c {
  fill: currentColor;
  d: path("M13 7C13 9.20914 11.2091 11 9 11C6.79086 11 5 9.20914 5 7C5 4.79086 6.79086 3 9 3C11.2091 3 13 4.79086 13 7ZM8 13H10C13.866 13 17 16.134 17 20C17 21.1046 16.1046 22 15 22H3C1.89543 22 1 21.1046 1 20C1 16.134 4.13401 13 8 13Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zuozovbmq {
  d: path("M17.0623 3C17.6791 4.2432 18 5.6122 18 7C18 8.3878 17.6791 9.7568 17.0623 11M21.3693 3C21.7872 4.2922 22 5.6419 22 7C22 9.282 21.3993 11.5238 20.2583 13.5");
}

</style>
