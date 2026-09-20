<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyicr-b7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:square-foot-sharp" /></template>
<style>
.lyicr-b7n {
  fill: currentColor;
  d: path("M3 21V2.45l4.1 4.1L5.75 7.9l.7.7L7.8 7.25l2.6 2.6l-1.35 1.35l.7.7l1.35-1.35l2.6 2.6l-1.35 1.35l.7.7l1.35-1.35l2.6 2.6l-1.35 1.35l.7.7l1.35-1.35L21.55 21zm3-3h8.3L6 9.7z");
}

</style>
