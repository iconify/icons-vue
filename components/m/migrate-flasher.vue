<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e3dtm8xwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:migrate-flasher" /></template>
<style>
.e3dtm8xwv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 41.03L43.5 24L4.5 6.97m39.082 21.067l-9.143 4.318l6.729 5.047l-9.729 3.628");
}

</style>
