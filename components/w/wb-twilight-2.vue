<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtnyc2-wv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wb-twilight-2" /></template>
<style>
.rtnyc2-wv {
  fill: currentColor;
  d: path("M2.5 19.5v-1h19v1zM6.116 15q.346-2.175 2.008-3.588T12 10t3.876 1.413T17.884 15z");
}

</style>
