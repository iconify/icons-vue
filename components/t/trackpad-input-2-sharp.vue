<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1628x9yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:trackpad-input-2-sharp" /></template>
<style>
.n1628x9yi {
  fill: currentColor;
  d: path("M2 19V3h19v6h-2V5H4v12h1.8l1.975 2zm12.825 3q-.6 0-1.15-.225t-.975-.65L7.6 16l1.6-1.65l2.8.825V7h2v7h1V6h2v8h1v-2h2v2h1v-2h2v6q0 1.65-1.175 2.825T19 22z");
}

</style>
