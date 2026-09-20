<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcpvzkb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mic-noise-cancel-low" /></template>
<style>
.bcpvzkb-g {
  fill: currentColor;
  d: path("M11 21V3h2v18h-2Zm-4.675-2.625l-1.4-1.4q1-1 1.538-2.275T7 12q0-1.425-.537-2.7T4.925 7.025l1.4-1.425Q7.6 6.875 8.288 8.525t.687 3.45q0 1.8-.688 3.463t-1.962 2.937Zm-2.8-2.825L2.1 14.125q.425-.425.663-.988T3 11.976q0-.6-.238-1.15T2.1 9.85l1.425-1.425q.725.7 1.113 1.625t.387 1.925q0 1-.388 1.938T3.526 15.55ZM15 13v-2h6v2h-6Z");
}

</style>
