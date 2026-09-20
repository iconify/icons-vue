<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vw8m6y3kh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:turn-slight-left" /></template>
<style>
.vw8m6y3kh {
  fill: currentColor;
  d: path("M13 20v-7.6l-5-5v2.25H6V4h5.65v2H9.4l5.025 5.025q.275.275.425.638t.15.762V20z");
}

</style>
