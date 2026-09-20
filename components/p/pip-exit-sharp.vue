<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fumev6hpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pip-exit-sharp" /></template>
<style>
.fumev6hpg {
  fill: currentColor;
  d: path("M2 20v-9h9V4h11v16zm15.075-3.5l1.425-1.425L15.4 12H18v-2h-6v6h2v-2.575zM2 9V4h7v5z");
}

</style>
