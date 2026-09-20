<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="u0gn0sbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:upwards-button" /></template>
<style>
.u0gn0sbvj {
  fill: var(--svg-color--db4437, #db4437);
  d: path("M92.41 88.77H35.59c-.97 0-1.88-.53-2.34-1.39c-.47-.86-.43-1.9.1-2.72l28.4-44.21c.49-.76 1.34-1.22 2.25-1.22s1.75.47 2.25 1.22l28.4 44.21c.53.82.57 1.86.1 2.72s-1.37 1.39-2.34 1.39");
}

</style>
