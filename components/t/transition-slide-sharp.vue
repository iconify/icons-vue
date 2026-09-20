<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea0uyzmhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:transition-slide-sharp" /></template>
<style>
.ea0uyzmhg {
  fill: currentColor;
  d: path("M1 20V4h6v16zm8 0V4h14v16z");
}

</style>
