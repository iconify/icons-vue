<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vq4wcu2jz"/><circle class="u1l7rqbek"/><path class="tv5w3ab-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-category" /></template>
<style>
.tv5w3ab-g {
  fill: currentColor;
  d: path("M3 13.5h8v8H3z");
}

.u1l7rqbek {
  cx: 17.5px;
  cy: 17.5px;
  r: 4.5px;
  fill: currentColor;
}

.vq4wcu2jz {
  fill: currentColor;
  d: path("m12 2l-5.5 9h11z");
}

</style>
