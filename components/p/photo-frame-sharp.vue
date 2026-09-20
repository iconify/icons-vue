<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqgp9vzfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:photo-frame-sharp" /></template>
<style>
.dqgp9vzfn {
  fill: currentColor;
  d: path("M5 21v-2H1V4h22v15h-4v2zm0-6h14l-4.5-6l-3.5 4.5l-2.5-3z");
}

</style>
