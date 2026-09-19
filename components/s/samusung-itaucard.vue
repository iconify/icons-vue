<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(-45 24 24)" class="akwdg930w"/><path class="qhx12q8_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:samusung-itaucard" /></template>
<style>
.akwdg930w {
  width: 34.12px;
  height: 24.085px;
  x: 6.94px;
  y: 11.958px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.018px;
  ry: 5.018px;
}

.qhx12q8_r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.938 18.403c-.136.722-.64 1.219-1.385 1.318m2.602-.905c-.264 1.109-.92 1.917-2.17 2.27m3.465-1.713c-.57 1.703-1.629 2.593-2.974 3.004m4.309-2.581c-.84 2.432-2.28 3.443-3.963 3.885");
}

</style>
