<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucrncv-ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pyramid" /></template>
<style>
.ucrncv-ks {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2.1809 16.032L12 2L21.8191 16.032C22.1736 16.5385 21.988 17.2422 21.4298 17.5081L12 22L2.5702 17.5081C2.012 17.2422 1.8264 16.5385 2.1809 16.032ZM12 2L12 22");
}

</style>
