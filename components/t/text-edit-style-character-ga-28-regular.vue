<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="uv3m0pkgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-edit-style-character-ga-28-regular" /></template>
<style>
.uv3m0pkgs {
  fill: currentColor;
  d: path("M21.069 9a3.932 3.932 0 0 1 2.78 6.712l-7.763 7.763a3.75 3.75 0 0 1-1.64.96l-5.493 1.538a.75.75 0 0 1-.925-.925l1.538-5.493a3.73 3.73 0 0 1 .96-1.64l7.762-7.764A3.93 3.93 0 0 1 21.069 9m0 1.5c-.645 0-1.264.256-1.72.712l-7.763 7.763a2.25 2.25 0 0 0-.575.984l-1.179 4.208l4.21-1.178c.371-.104.71-.302.984-.575l7.762-7.763a2.434 2.434 0 0 0-1.72-4.151M13.25 3a.75.75 0 0 1 .75.75V7.5h1.75a.75.75 0 0 1 0 1.5H14v4.025l-1.5 1.5V3.75a.75.75 0 0 1 .75-.75m-3.5 1a.75.75 0 0 1 .75.718v.004c.005.027.001.06.001.088q0 .078-.003.215a8 8 0 0 1-.063.748a9 9 0 0 1-.652 2.37c-.798 1.836-2.462 3.886-5.83 4.83a.751.751 0 0 1-.405-1.446c2.881-.806 4.217-2.507 4.858-3.982a7.4 7.4 0 0 0 .543-1.967l.007-.078H3.75a.75.75 0 0 1 0-1.5z");
}

</style>
