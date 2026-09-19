<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="i7rxrj50u"/><path class="bgy34fbxq"/></g><path class="d2so08zqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:prompt-post" /></template>
<style>
.bgy34fbxq {
  d: path("M38.553 23.68H25.236v12.413");
}

.d2so08zqe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.33 42.5h31.34");
}

.i7rxrj50u {
  d: path("M13.044 36.595a4.7 4.7 0 0 1-4.714-4.708V10.208A4.7 4.7 0 0 1 13.044 5.5h21.911a4.7 4.7 0 0 1 4.714 4.708v8.338c0 2.939.115 3.988-1.824 5.925L27.532 34.773c-1.463 1.461-3.863 1.822-5.931 1.822z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
