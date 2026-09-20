<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4xcey-cy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:watch-button-outline" /></template>
<style>
.c4xcey-cy {
  fill: currentColor;
  d: path("m5.056 21.825l-.829-.561q1.24-2.239 1.417-4.514T5.821 12q0-2.45-.177-4.734q-.177-2.285-1.417-4.504l.829-.562q.382.702.654 1.397q.273.695.473 1.403H8.23q1.4.006 2.373 1.024t.973 2.482v7.019q0 1.458-.973 2.47q-.973 1.01-2.373 1.01H6.183q-.2.709-.463 1.413t-.664 1.407m12.598-6.536L14.48 12l3.173-3.27l.708.714l-1.96 2.056H21v1h-4.598l1.96 2.08zM6.425 18h1.806q.979 0 1.662-.732t.684-1.768V8.48q0-1.016-.684-1.748T8.231 6H6.419q.287 1.437.347 2.91q.061 1.475.061 3.09q0 1.621-.058 3.102T6.425 18m.402-6");
}

</style>
