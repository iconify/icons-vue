<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd_f2la9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:signal-cellular-alt-sharp" /></template>
<style>
.nd_f2la9e {
  fill: currentColor;
  d: path("M6 19v-4h1.616v4zm5.808 0v-9h1.615v9zm5.577 0V5H19v14z");
}

</style>
