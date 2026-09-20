<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng93zktqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nightlife-rounded" /></template>
<style>
.ng93zktqk {
  fill: currentColor;
  d: path("M6.885 18.5v-5.346l-3.933-5.9q-.277-.396-.04-.825T3.625 6h7.52q.474 0 .712.429q.237.429-.04.825l-3.933 5.9V18.5h1.5q.213 0 .357.144t.143.357t-.143.356t-.357.143h-4q-.212 0-.356-.144t-.144-.357t.144-.356t.356-.143zM5.284 9h4.2l1.361-2H3.923zm8.33 9.772q-.73-.729-.73-1.77t.729-1.771t1.77-.731q.399 0 .76.134q.362.133.74.45V6.808q0-.343.233-.576T17.692 6H20q.356 0 .62.255q.264.256.264.62q0 .366-.264.63t-.62.264h-2.116V17q0 1.042-.728 1.77q-.728.73-1.769.73t-1.771-.728");
}

</style>
