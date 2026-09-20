<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb90m9fpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:soap-sharp" /></template>
<style>
.gb90m9fpg {
  fill: currentColor;
  d: path("M18 21H3v-9.563l9.26-6l.894.97l-2.277 3.785H19v1h-6v2.27h8v1h-8v2.269h7v1h-7V20h5zM15.06 7.462q-.368-.365-.368-.882t.365-.885t.882-.368t.885.365t.368.882t-.365.885t-.882.368t-.885-.365m1.733-3.522q-.293-.291-.293-.707t.291-.709t.707-.293t.709.29t.293.708t-.291.708t-.707.294t-.709-.291m2.16 3.626q-.434-.433-.434-1.066t.434-1.066Q19.387 5 20.019 5t1.067.434q.433.433.433 1.066t-.433 1.066T20.019 8t-1.066-.434");
}

</style>
