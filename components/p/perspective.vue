<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fq1r9igwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:perspective" /></template>
<style>
.fq1r9igwd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 2V12M12 12V22M12 12H2M12 12H22M5 9.62V14.49C5 15.38 5.592 16.17 6.4506 16.41L16.4506 19.27C17.7282 19.64 19 18.68 19 17.35V7.47C19 6.2 17.826 5.25 16.5809 5.52L6.5809 7.66C5.6588 7.86 5 8.67 5 9.62Z");
}

</style>
