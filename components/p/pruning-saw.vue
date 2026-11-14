<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vetysvbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pruning-saw" /></template>
<style>
.vetysvbwg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.867 12.061q3.699-9.273 14.562-10.308q.073-.007.147.001q.073.007.144.029t.136.057t.122.082t.103.104t.082.123q.034.065.055.136q.022.07.029.144q.014.149-.03.292l-1 3.25q-.031.099-.088.187t-.135.156q-.079.069-.173.114q-.095.045-.198.062l-2.471.412l-.412 2.471q-.017.104-.063.199q-.045.095-.114.174q-.07.079-.158.135q-.089.057-.189.087l-2.041.613l-.433 3.025q-.022.158-.107.294q-.086.135-.219.224l-2.666 1.777V20q0 2.25-2.25 2.25H4q-2.25 0-2.25-2.25v-3q0-.159.065-.305t.183-.252zm.645 1.437L3.25 17.334V20q0 .75.75.75h5.5q.75 0 .75-.75v-4.155zM4.5 17.75q0-2.25 2.25-2.25T9 17.75T6.75 20T4.5 17.75");
}

</style>
