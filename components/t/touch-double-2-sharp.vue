<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w49u-pb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:touch-double-2-sharp" /></template>
<style>
.w49u-pb7j {
  fill: currentColor;
  d: path("M8.975 22L2.65 13.95L4.3 12.3l3.2 1.925V7h2v5H11V5.25h2V12h7v10zm-5.4-12.9Q3.5 8.825 3.5 8.55V8q0-2.9 2.038-4.95T10.5 1q2.9 0 4.95 2.05T17.5 8q0 .275-.038.638L17.426 9l-2-.225l.038-.288Q15.5 8.2 15.5 8q0-2.075-1.463-3.537T10.5 3Q8.4 3 6.95 4.463T5.5 8v.4q0 .2.05.4z");
}

</style>
