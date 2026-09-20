<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2--awb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:trackpad-input-2-sharp" /></template>
<style>
.t2--awb6o {
  fill: currentColor;
  d: path("M3 18V4h17v5.058h-1V5H4v12h2.416l.993 1zm11.668 3q-.5 0-.945-.186t-.807-.547l-4.354-4.344l1.004-1.054l2.78.652V8.02h1v6.308h1.77V6.75h1v7.577h1.769V12h1v2.327h1.769V12h1v5.5q0 1.458-1.021 2.479T18.153 21z");
}

</style>
