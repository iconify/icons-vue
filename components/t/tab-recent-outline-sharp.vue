<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw1drxbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tab-recent-outline-sharp" /></template>
<style>
.lw1drxbnc {
  fill: currentColor;
  d: path("M15.165 20.836Q14 19.67 14 18t1.165-2.835T18 14t2.836 1.165T22 18t-1.164 2.836T18 22t-2.835-1.164m4.485-.64l.546-.546l-1.811-1.811v-2.723h-.77v3.046zM13.77 9.04H20v3.28q.28.079.521.191q.24.113.479.265V5H3v14h9.089q-.054-.244-.072-.494T12 18H4V6h9.77zM4 17.385V18V6z");
}

</style>
