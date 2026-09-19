<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nalr1yb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rijnmond" /></template>
<style>
.nalr1yb3q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 13.013c4.111 2.692 4.475 9.75-2 10.623s-11.788-1.528-11.788-1.528V4.5h10.987c9.022 0 14.26 6.185 14.26 14.188s-5.092 10.405-5.092 10.405L37.788 43.5H28.33l-6.185-11.278h-2.983V43.5h-8.95V30.84");
}

</style>
