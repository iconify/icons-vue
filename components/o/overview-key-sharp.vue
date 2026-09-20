<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n18gh5b6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:overview-key-sharp" /></template>
<style>
.n18gh5b6l {
  fill: currentColor;
  d: path("M1 19V5h14v14zm16 0V5h2v14zm4 0V5h2v14z");
}

</style>
