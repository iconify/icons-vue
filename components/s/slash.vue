<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq1_76izs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:slash" /></template>
<style>
.qq1_76izs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m16.679 3.819l-8 17q-.032.067-.076.127q-.044.059-.098.109q-.055.049-.118.088t-.133.063q-.069.025-.143.036t-.146.007q-.074-.003-.146-.021t-.138-.049q-.135-.064-.236-.174q-.1-.111-.151-.251t-.043-.289q.007-.149.07-.284l8-17q.064-.135.174-.236q.111-.1.251-.151t.289-.043t.284.07q.067.032.127.076q.059.044.109.098q.049.055.088.118t.063.133q.025.069.036.143t.007.146q-.003.074-.021.146t-.049.138");
}

</style>
