<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wwbjllbpy"/><path class="lukv08b5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:redditoria" /></template>
<style>
.lukv08b5f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.197 22.753V42.5a1 1 0 0 0 1 1h18.715a1.887 1.887 0 0 0 1.36-3.195l-16.88-17.552");
}

.wwbjllbpy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.197 4.5h11.074a9.126 9.126 0 0 1 9.127 9.126v0a9.126 9.126 0 0 1-9.127 9.127H13.197h0V5.5a1 1 0 0 1 1-1");
}

</style>
