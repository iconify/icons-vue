<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="v0keepb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:pix-logo-bold" /></template>
<style>
.v0keepb9s {
  fill: currentColor;
  d: path("m238.16 113.89l-96-96a20 20 0 0 0-28.22 0l-96 96.05a20 20 0 0 0 0 28.22l96.05 96a20 20 0 0 0 28.22 0l96-96a20 20 0 0 0 0-28.22ZM128 37.68L174.32 84H160a12 12 0 0 0-8.49 3.51L128 111l-23.51-23.49A12 12 0 0 0 96 84H81.68ZM57.68 108H91l20 20l-20 20H57.68l-20-20ZM128 218.32L81.68 172H96a12 12 0 0 0 8.49-3.51L128 145l23.51 23.52A12 12 0 0 0 160 172h14.32ZM198.32 148H165l-20-20l20-20h33.35l20 20Z");
}

</style>
