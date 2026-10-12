<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gocnembpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vest-sharp" /></template>
<style>
.gocnembpf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.03 3.6l3.44 5.55l.53.85l.53-.85l3.44-5.55l.53-.85l.21.98l.58 2.79l.21.98l.71.71l.58.58l.71.71v9.75l-.87.5l-1.76 1l-.87.5l-.94-.35l-2.12-.8l-.94-.35l-.94.35l-2.12.8l-.94.35l-.87-.5l-1.76-1l-.87-.5V9.5l.71-.71l.58-.58l.71-.71l.21-.98l.58-2.79l.21-.98zM12 11.75V18");
}

</style>
