<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2cd8nubp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:recent-patient" /></template>
<style>
.b2cd8nubp {
  fill: currentColor;
  d: path("M4 20v-2.8q0-.85.438-1.562T5.6 14.55q1.55-.775 3.15-1.162T12 13q.5 0 1 .038t1 .112V20zm5.175-9.175Q8 9.65 8 8t1.175-2.825T12 4t2.825 1.175T16 8t-1.175 2.825T12 12t-2.825-1.175M18 24v-5h-2v-6h6l-2 4h2z");
}

</style>
