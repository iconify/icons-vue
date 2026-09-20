<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilawgs16q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:reviews-sharp" /></template>
<style>
.ilawgs16q {
  fill: currentColor;
  d: path("M2 22V2h20v16H6zm7.075-7.75L12 12.475l2.925 1.775l-.775-3.325l2.6-2.25l-3.425-.275L12 5.25L10.675 8.4l-3.425.275l2.6 2.25z");
}

</style>
