<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7a8pckfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tote-bag-reusable" /></template>
<style>
.f7a8pckfw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.75 6.5q0-4.75 4.75-4.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 4.359-4 4.718v2.098q2.5.404 2.5 3.309v6.25q0 3.375-3.375 3.375H6.625q-3.375 0-3.375-3.375v-6.25q0-2.905 2.5-3.309V8q0-1.968 1.391-3.359T10.5 3.25t3.359 1.391T15.25 8v1.25h1.5zm-3 1.5v1.25h-6.5V8q0-3.25 3.25-3.25q1.625 0 2.438.813q.812.812.812 2.437");
}

</style>
