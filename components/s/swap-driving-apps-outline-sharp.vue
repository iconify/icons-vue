<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5xl9032x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:swap-driving-apps-outline-sharp" /></template>
<style>
.y5xl9032x {
  fill: currentColor;
  d: path("m16.154 7.346l-.72-.707l1.6-1.6H7.566v-1h9.468l-1.6-1.6l.708-.72l2.82 2.82zM5 19h14v-4.846H5zm3.22-1.627q.319-.32.319-.796t-.32-.796t-.796-.32q-.477 0-.796.32t-.32.796t.32.796t.796.32t.796-.32m9.154 0q.32-.32.32-.796t-.32-.796t-.796-.32q-.477 0-.796.32t-.32.796t.32.796t.796.32t.796-.32M4 13.153h14.585L17.112 9H5.946l1.6 1.6l-.708.72L4.02 8.5l2.82-2.82l.707.72l-1.6 1.6H17.84L20 14.154V22h-1.23v-2H5.23v2H4zm1 1V19z");
}

</style>
