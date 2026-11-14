<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o270cccnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin" /></template>
<style>
.o270cccnw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 2.75h-1.5q-2.5 0-2.5 2.5v2.74q0 .291-.157.537l-1.514 2.38q-.794 1.248-.083 2.546t2.192 1.297h2.062V21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-6.25h2.062q1.48 0 2.192-1.297q.711-1.298-.083-2.546l-1.514-2.38q-.157-.246-.157-.537V5.25q0-1.036-.732-1.768T12.75 2.75");
}

</style>
