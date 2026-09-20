<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft04tudcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tap-and-play-outline-sharp" /></template>
<style>
.ft04tudcg {
  fill: currentColor;
  d: path("M6 11.462V2h12v20h-1V5.5H7v5.962zM6 22v-1.384q.571 0 .978.406t.407.978zm3.77 0q0-1.573-1.099-2.671T6 18.23v-1q1.987 0 3.378 1.39T10.77 22zm3.384 0q0-2.984-2.085-5.07Q8.984 14.847 6 14.847v-1q1.692 0 3.18.642t2.589 1.743t1.743 2.589t.642 3.18zM7 4.5h10V3H7zm0 0V3z");
}

</style>
