<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqze662ge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:soap-outline-sharp" /></template>
<style>
.nqze662ge {
  fill: currentColor;
  d: path("M15.06 7.462q-.368-.365-.368-.882t.365-.885t.882-.368t.885.365t.368.882t-.365.885t-.882.368t-.885-.365m3.893.104q-.434-.433-.434-1.066t.434-1.066Q19.387 5 20.019 5t1.067.434q.433.433.433 1.066t-.433 1.066T20.019 8t-1.066-.434m-2.16-3.626q-.293-.291-.293-.707t.291-.709t.707-.293t.709.29t.293.708t-.291.708t-.707.294t-.709-.291M18 21H3v-9.563l9.26-6l.894.97l-2.277 3.785H19v1H9.104l2.483-4.138L4 11.973V20h14zm-5-6.538v-1h8v1zm0 3.269v-1h7v1zm-4.5-3.916");
}

</style>
