<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lhowc-axs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slash-forward-16-regular" /></template>
<style>
.lhowc-axs {
  fill: currentColor;
  d: path("M10.44 2.037a.5.5 0 0 1 .273.652l-4.5 11a.5.5 0 0 1-.926-.378l4.5-11a.5.5 0 0 1 .652-.274");
}

</style>
