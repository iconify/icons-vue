<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvw3qjbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:waves-ladder-sharp" /></template>
<style>
.zvw3qjbdw {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 15L8 4C8 2.8954 7.1046 2 6 2C4.8954 2 4 2.8954 4 4L4 5M16 15L16 4C16 2.8954 15.1046 2 14 2C12.8954 2 12 2.8954 12 4L12 5M8 8L16 8M8 12L16 12M1.8258 20.2551L2 20C3.821 17.3333 5.179 17.3333 7 20C8.821 22.6667 10.179 22.6667 12 20C13.821 17.3333 15.179 17.3333 17 20C18.821 22.6667 20.179 22.6667 22 20L22.1742 19.7449");
}

</style>
