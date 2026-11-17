<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpg34ybzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wave-sine-fill-sharp" /></template>
<style>
.bpg34ybzx {
  fill: currentColor;
  d: path("M3.498 8.888c.376-.675.77-1.344 1.221-1.972c.351-.488.743-.964 1.221-1.333C6.39 5.237 6.925 5 7.5 5c1.219 0 2.124 1.003 2.781 1.916c.451.628.845 1.297 1.221 1.972c.488.876.944 1.769 1.392 2.665Q15.618 17 16.5 17t3.606-5.447a1 1 0 1 1 1.788.894a67 67 0 0 1-1.392 2.665c-.376.675-.77 1.344-1.221 1.972c-.351.488-.743.964-1.221 1.333c-.45.346-.985.583-1.56.583c-1.219 0-2.124-1.003-2.781-1.916a20 20 0 0 1-1.221-1.972a67 67 0 0 1-1.392-2.665Q8.382 7 7.5 7t-3.606 5.447a1 1 0 1 1-1.788-.894c.448-.896.904-1.789 1.392-2.665");
}

</style>
