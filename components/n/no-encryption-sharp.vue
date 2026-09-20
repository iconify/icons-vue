<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_mhy7a1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:no-encryption-sharp" /></template>
<style>
.g_mhy7a1x {
  fill: currentColor;
  d: path("M20 17.15L10.85 8H15V6q0-1.25-.862-2.125T12.025 3t-2.1.863T9.075 6v.225L7.25 4.4q.55-1.525 1.875-2.463t2.9-.937Q14.1 1 15.55 2.463T17 6v2h3zm.5 6.15L19.2 22H4V8.1h1.3L.7 3.5l1.4-1.4l19.8 19.8zm-9.9-9.85q-.275.275-.425.638t-.15.787q0 .825.588 1.413t1.412.587q.425 0 .788-.15t.637-.425z");
}

</style>
