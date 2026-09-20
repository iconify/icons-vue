<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kf-f7wbzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:picture-in-picture-alt-outline-sharp" /></template>
<style>
.kf-f7wbzk {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h16V6H4zm0 0V6zm7-1h8v-6h-8zm2-2v-2h4v2z");
}

</style>
