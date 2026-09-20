<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="hc_5wyobp"/><circle class="iz4ladcvf"/><path class="aigfh7b4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pop-avain" /></template>
<style>
.aigfh7b4v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.78 23.402s12.771 12.08 18.306 17.615s.34.335.675 0l2.58-2.581s.302-.285 0-.587l-2.15-2.15l3.141-3.14c.081-.081.333-.381 0-.714l-.623-.624s-.258-.309-.567 0l-1.08 1.08l-1.348-1.347l1.101-1.101c.168-.19.096-.405 0-.545c-.097-.144-.734-.735-.734-.735s-.231-.28-.51 0l-3.219 3.218l-1.42-1.42l.375-.419c.12-.12.252-.355.043-.564l-.775-.774s-.212-.29-.5 0l-.443.442l-9.296-8.695");
}

.hc_5wyobp {
  cx: 14.746px;
  cy: 15.08px;
  r: 9.246px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.iz4ladcvf {
  cx: 14.746px;
  cy: 15.197px;
  r: 4.866px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
