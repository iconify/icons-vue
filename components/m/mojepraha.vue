<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ry83ffbng"/><path class="yc86yibst"/><path class="mu89qjmlo"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mojepraha" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.mu89qjmlo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.424 30.75c-.42 0-.84-.42-.84-.84v-4.72m2.76-2.805v8.394m0-3.462c0-1.154.945-2.099 2.099-2.099s2.098.945 2.098 2.099v3.462m-9.498-14.467z");
}

.ry83ffbng {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.543 17.845c0-.843.69-1.533 1.533-1.533s1.533.69 1.533 1.533v2.453m-3.066-3.985v3.986m3.066-2.454c0-.843.69-1.533 1.533-1.533s1.533.69 1.533 1.533v2.453m3.18.077c-.843 0-1.533-.69-1.533-1.533v-.997c0-.843.69-1.533 1.533-1.533s1.533.69 1.533 1.533v.997c0 .843-.69 1.533-1.533 1.533m3.205-2.6v4.599c0 .843-.69 1.533-1.533 1.533c-.383 0-.767-.153-1.073-.46m7.119-3.839c-.23.46-.767.767-1.303.767c-.844 0-1.533-.69-1.533-1.533v-.997c0-.843.69-1.533 1.533-1.533s1.533.69 1.533 1.533v.537h-3.066M9.5 30.885V22.49h2.728c1.574 0 2.833 1.26 2.833 2.833s-1.26 2.833-2.833 2.833H9.5m7.386-.869c0-1.154.945-2.098 2.099-2.098m-2.099 0v5.561m20.774-1.886c0 1.154-.944 2.099-2.098 2.099s-2.098-.945-2.098-2.099V27.5c0-1.154.944-2.098 2.098-2.098s2.099.944 2.099 2.098");
}

.yc86yibst {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 30.963c-.42 0-.84-.42-.84-.84v-4.721m-13.075 3.249c0 1.154-.945 2.099-2.099 2.099s-2.098-.945-2.098-2.099v-1.364c0-1.154.944-2.098 2.098-2.098s2.099.944 2.099 2.098");
}

</style>
