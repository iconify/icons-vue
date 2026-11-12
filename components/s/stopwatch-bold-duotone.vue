<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6cqcqlkv"/><path class="ai2yz9bsx"/><path class="t6l01zbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stopwatch-bold-duotone" /></template>
<style>
.ai2yz9bsx {
  fill: currentColor;
  d: path("M12 8.25C12.4142 8.25 12.75 8.58579 12.75 9V13C12.75 13.4142 12.4142 13.75 12 13.75C11.5858 13.75 11.25 13.4142 11.25 13V9C11.25 8.58579 11.5858 8.25 12 8.25Z");
}

.t6l01zbxr {
  fill: currentColor;
  d: path("M14 1C14.4142 1 14.75 1.33579 14.75 1.75C14.75 2.16421 14.4142 2.5 14 2.5H10C9.58579 2.5 9.25 2.16421 9.25 1.75C9.25 1.33579 9.58579 1 10 1H14Z");
}

.v6cqcqlkv {
  fill: currentColor;
  d: path("M12 22C16.9706 22 21 17.9706 21 13C21 8.02944 16.9706 4 12 4C7.02944 4 3 8.02944 3 13C3 17.9706 7.02944 22 12 22Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
