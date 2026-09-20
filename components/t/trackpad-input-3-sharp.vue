<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyvw0tbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:trackpad-input-3-sharp" /></template>
<style>
.hyvw0tbhy {
  fill: currentColor;
  d: path("m13.652 21l-5.09-5.077l1.004-1.054l2.78.652V8.02h1v6.308h1.77V6.75h1v7.577h1.769V8.519h1v5.808h1.769v-.5h1V17.5q0 1.458-1.021 2.479T18.153 21zM3 18V4h17v1H4v12h2.416l.993 1z");
}

</style>
