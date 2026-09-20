<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps4wsqybg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:unfold-more-outline-rounded" /></template>
<style>
.ps4wsqybg {
  fill: currentColor;
  d: path("m12 18.1l2.325-2.325q.3-.3.725-.3t.725.3t.3.725t-.3.725L12.7 20.3q-.15.15-.325.213t-.375.062t-.375-.062t-.325-.213l-3.075-3.075q-.3-.3-.3-.725t.3-.725t.725-.3t.725.3zM12 6L9.675 8.325q-.3.3-.725.3t-.725-.3t-.3-.725t.3-.725L11.3 3.8q.15-.15.325-.213T12 3.526t.375.063t.325.212l3.075 3.075q.3.3.3.725t-.3.725t-.725.3t-.725-.3z");
}

</style>
