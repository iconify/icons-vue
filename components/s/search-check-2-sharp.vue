<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b91vswbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:search-check-2-sharp" /></template>
<style>
.b91vswbbi {
  fill: currentColor;
  d: path("m8.95 13.55l5.65-5.675l-1.425-1.425L8.95 10.7L6.825 8.6L5.4 10zM10 18q-3.35 0-5.675-2.325T2 10t2.325-5.675T10 2t5.675 2.325T18 10q0 1.4-.437 2.638T16.325 14.9L22 20.6L20.6 22l-5.7-5.675q-1.025.8-2.262 1.238T10 18");
}

</style>
