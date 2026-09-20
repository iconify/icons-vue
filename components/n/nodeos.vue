<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":274};
const content = `<path class="co23r5jxn"/><path class="cxubzac3o"/><path class="q0wt4-b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:nodeos" /></template>
<style>
.co23r5jxn {
  fill: var(--svg-color--00a, #00a);
  d: path("M96.865 58.153L128 40.177l31.135 17.976v43.941l34.595 19.973V38.18L128 .23L62.27 38.18v83.887l34.595-19.973z");
}

.cxubzac3o {
  fill: var(--svg-color--0aa, #0aa);
  d: path("M186.811 126.062L128 160.016l-58.811-33.954L128 92.107z");
}

.q0wt4-b9v {
  fill: var(--svg-color--00a, #00a);
  d: path("M62.27 130.057L0 166.008v71.904l62.27 35.95l62.27-35.95v-71.904zm0 31.957l34.595 19.973v39.946L62.27 241.906l-34.594-19.973v-39.946zm131.46 79.892l-34.595-19.973v-7.989l-27.676-15.979v39.947l62.271 35.95l62.27-35.95v-15.979l-83.027-47.936l20.757-11.984l34.594 19.974v7.989L256 205.954v-39.946l-62.27-35.952l-62.271 35.952v15.979l83.027 47.935z");
}

</style>
