<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axcl0-nzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:user-star" /></template>
<style>
.axcl0-nzo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.818 5.068Q4.5 6.386 4.5 8.25t1.318 3.182T9 12.75t3.182-1.318T13.5 8.25t-1.318-3.182T9 3.75T5.818 5.068m13.35 2.982l.177.315q.169.301.508.368l.354.072q.769.154 1.011.899q.243.745-.288 1.322l-.246.266q-.234.254-.194.596l.042.36q.091.778-.543 1.239t-1.347.135l-.329-.152q-.313-.144-.626 0l-.328.151q-.714.328-1.348-.133q-.634-.462-.543-1.24l.042-.359q.04-.343-.194-.597l-.245-.265q-.532-.578-.289-1.323q.242-.745 1.01-.899l.355-.071q.339-.068.508-.369l.177-.315q.385-.683 1.168-.683t1.167.682zM1.75 20q0-2.427 2.213-4.015Q6.03 14.5 9 14.5t5.037 1.485Q16.25 17.573 16.25 20q0 1.75-1.75 1.75h-11q-1.75 0-1.75-1.75");
}

</style>
