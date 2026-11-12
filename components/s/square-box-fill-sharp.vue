<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ns8hg4bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-box-fill-sharp" /></template>
<style>
.ns8hg4bpb {
  fill: currentColor;
  d: path("M2 3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Zm2 1v16h16V4Zm4.629 4.665L7.5 8.107l4.057-2.004c.279-.137.607-.137.886 0L16.5 8.107L12 10.329ZM6.5 9.844l4.5 2.222v5.555l-3.943-1.947a1 1 0 0 1-.557-.896Zm6.5 2.222l4.5-2.222v4.934a1 1 0 0 1-.557.896L13 17.621Z");
}

</style>
