<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivbdl2b4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speed-camera" /></template>
<style>
.ivbdl2b4t {
  fill: currentColor;
  d: path("m17.525 15l-2.175-1.25l3.5-2.6L21 12.4zM4 20v-2h5v-5.95l-3-1.725q-.725-.425-.937-1.212T5.275 7.6l1.5-2.6q.425-.725 1.213-.937t1.512.212l9.525 5.5l-6.1 4.55l-1.925-1.1V18q0 .825-.588 1.413T9 20z");
}

</style>
