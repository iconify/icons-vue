<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-2c69b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tip-jar" /></template>
<style>
.x-2c69b4s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.961 5.75h3.877l.312-2.5h-3.564zm5.389 0h2.15q2.25 0 2.25 2.25q0 1.565-1.089 2.042q1.03 2.303.648 6.218q-.536 5.49-3.809 5.49h-7q-3.273 0-3.809-5.49q-.382-3.915.648-6.218Q4.25 9.565 4.25 8q0-2.25 2.25-2.25h1.914l.858-3.432q.016-.06.04-.117q.025-.058.059-.11t.076-.098t.091-.084t.104-.068t.114-.05t.12-.031t.124-.01h5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .047-.006.093zm-8.438 4.5q-1.111 1.941-.728 5.865q.403 4.135 2.316 4.135h7q1.913 0 2.316-4.135q.383-3.924-.728-5.865z");
}

</style>
