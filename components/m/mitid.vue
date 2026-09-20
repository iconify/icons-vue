<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s9_nx8b6i"/><circle class="ghnh1rt9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mitid" /></template>
<style>
.ghnh1rt9p {
  cx: 14.268px;
  cy: 19.116px;
  r: 5.772px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.s9_nx8b6i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.38 34.656V13.344h5.796a9.324 9.324 0 0 1 9.324 9.324v2.664a9.324 9.324 0 0 1-9.324 9.324zm-23.88 0zc0-5.395 4.373-9.768 9.768-9.768s9.768 4.373 9.768 9.768s-19.536 0-19.536 0");
}

</style>
