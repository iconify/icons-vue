<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7l3q6h_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:phi-fill" /></template>
<style>
.s7l3q6h_k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.9117 5.7195C6.3159 6.6729 6 7.7747 6 8.899C6 12.2127 8.6863 14.899 12 14.899C15.3137 14.899 18 12.2127 18 8.899C18 6.0478 15.9935 3.5904 13.2 3.0202C13.1342 3.0068 13.0672 3 13 3C12.4477 3 12 3.4477 12 4L12 21");
}

</style>
