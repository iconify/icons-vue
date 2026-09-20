<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ohqf2phvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pin-12-filled" /></template>
<style>
.ohqf2phvj {
  fill: currentColor;
  d: path("M8.052 1.436a1.5 1.5 0 0 0-2.38.347L4.145 4.608l-2.33.928a.5.5 0 0 0-.169.818l1.647 1.647l-2.146 2.146l-.147.854l.854-.147L4 8.708l1.646 1.646a.5.5 0 0 0 .818-.168l.933-2.332l2.821-1.526a1.5 1.5 0 0 0 .347-2.38z");
}

</style>
