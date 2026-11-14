<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3g8wyb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:parallelogram" /></template>
<style>
.l3g8wyb1f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.414 4.25h7.985q1.716 0 2.727 1.387t.486 3.02l-2.812 8.75q-.753 2.344-3.214 2.343H6.601q-1.716 0-2.727-1.387t-.486-3.02L6.2 6.593q.753-2.344 3.214-2.343");
}

</style>
