<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0imvghmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stylus-outline" /></template>
<style>
.z0imvghmt {
  fill: currentColor;
  d: path("M4.175 21q-.525.125-.913-.262T3 19.825l1-4.775L8.95 20zm4.775-1L4 15.05L15.45 3.6q.575-.575 1.425-.575T18.3 3.6l2.1 2.1q.575.575.575 1.425T20.4 8.55zm7.925-15L6.525 15.35l2.125 2.125L19 7.125z");
}

</style>
