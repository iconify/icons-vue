<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylvvy19_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presenter-24-regular" /></template>
<style>
.ylvvy19_p {
  fill: currentColor;
  d: path("M20.25 12a.75.75 0 0 1 .51 1.3L16 17.72v2.03A2.25 2.25 0 0 1 13.75 22h-3.5A2.25 2.25 0 0 1 8 19.75v-2.03L3.24 13.3a.751.751 0 0 1 .51-1.3zM9.26 16.843a.75.75 0 0 1 .24.55v2.357c0 .414.336.75.75.75h3.5a.75.75 0 0 0 .75-.75v-2.357a.75.75 0 0 1 .24-.55l3.6-3.343H5.66zM14.252 9a2.25 2.25 0 0 1 2.235 2h-1.53a.75.75 0 0 0-.705-.5h-4.5a.75.75 0 0 0-.704.5H7.516A2.25 2.25 0 0 1 9.75 9zM12 2a3 3 0 1 1 0 6a3 3 0 0 1 0-6m0 1.5a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3");
}

</style>
