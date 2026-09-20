<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awddd2b9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:step-out-outline-rounded" /></template>
<style>
.awddd2b9p {
  fill: currentColor;
  d: path("M10.23 20.77Q9.5 20.037 9.5 19t.73-1.77T12 16.5t1.77.73t.73 1.77t-.73 1.77t-1.77.73t-1.77-.73M11.5 5.132l-2.765 2.72q-.14.141-.332.135q-.191-.007-.337-.154q-.141-.14-.141-.343t.14-.345l3.37-3.369q.242-.243.565-.243t.566.243l3.368 3.37q.147.145.154.353t-.16.354q-.145.14-.353.133t-.354-.153L12.5 5.115V13.5q0 .214-.143.357T12 14t-.357-.143t-.143-.357z");
}

</style>
