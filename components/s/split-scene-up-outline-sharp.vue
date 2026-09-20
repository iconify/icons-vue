<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s28m00bky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:split-scene-up-outline-sharp" /></template>
<style>
.s28m00bky {
  fill: currentColor;
  d: path("M4 21v-6h2v4h12v-4h2v6zm-2-8v-2h2V3h16v8h2v2zm16 6H6z");
}

</style>
