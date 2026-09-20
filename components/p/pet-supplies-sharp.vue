<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-jq8eb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pet-supplies-sharp" /></template>
<style>
.g-jq8eb5h {
  fill: currentColor;
  d: path("M9.5 22q-1.475 0-2.488-1.012T6 18.5q0-.225.063-.35t-.013-.2t-.2-.012T5.5 18q-1.475 0-2.488-1.012T2 14.5t1.013-2.488T5.5 11q.575 0 1.05.15t.9.45l4.15-4.15q-.3-.425-.45-.9T11 5.5q0-1.475 1.013-2.488T14.5 2t2.488 1.013T18 5.5q0 .225-.062.35t.012.2t.2.013T18.5 6q1.475 0 2.488 1.013T22 9.5t-1.012 2.488T18.5 13q-.575 0-1.05-.15t-.9-.45l-4.15 4.15q.3.425.45.9T13 18.5q0 1.475-1.012 2.488T9.5 22");
}

</style>
