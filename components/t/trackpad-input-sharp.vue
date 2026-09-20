<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hey1t5byj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:trackpad-input-sharp" /></template>
<style>
.hey1t5byj {
  fill: currentColor;
  d: path("M3 18V4h17v5.058h-1V5H4v12h2.416l.993 1zm15.154 3h-3.486q-.5 0-.945-.186t-.807-.547l-4.354-4.344l1.004-1.054l2.78.652V8.02h1v6.308h1.77v-4.27h1v4.27h1.769v-2.885h1v2.885h1.769v-.5h1V17.5q0 1.458-1.021 2.479T18.153 21");
}

</style>
