<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2bnb9bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stat-0" /></template>
<style>
.f2bnb9bzw {
  fill: currentColor;
  d: path("m12 19l-7-7l7-7l7 7z");
}

</style>
