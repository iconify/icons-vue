<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzqt9eb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-border-color" /></template>
<style>
.bzqt9eb7d {
  fill: currentColor;
  d: path("M22 24H2v-4h20zM13.06 5.19l3.75 3.75L7.75 18H4v-3.75zm4.82 2.68l-3.75-3.75l2.53-2.54l3.75 3.75z");
}

</style>
