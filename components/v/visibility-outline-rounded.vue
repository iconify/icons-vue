<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3eycvg6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:visibility-outline-rounded" /></template>
<style>
.h3eycvg6e {
  fill: currentColor;
  d: path("M14.591 14.091q1.063-1.062 1.063-2.591T14.59 8.909T12 7.846T9.409 8.91T8.346 11.5t1.063 2.591T12 15.154t2.591-1.063m-4.503-.678Q9.3 12.625 9.3 11.5t.788-1.912T12 8.8t1.913.788t.787 1.912t-.787 1.913T12 14.2t-1.912-.787M6.56 16.43q-2.474-1.57-3.997-4.116q-.125-.205-.178-.404t-.053-.411t.053-.41t.178-.406Q4.087 8.14 6.56 6.57T12 5t5.44 1.57t3.997 4.115q.125.205.178.404t.052.411t-.052.41t-.178.406q-1.523 2.545-3.997 4.115T12 18t-5.44-1.57m10.628-.917Q19.55 14.025 20.8 11.5q-1.25-2.525-3.613-4.012T12 6T6.813 7.488T3.2 11.5q1.25 2.525 3.613 4.013T12 17t5.188-1.487");
}

</style>
