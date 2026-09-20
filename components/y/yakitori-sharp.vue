<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9em1k2bk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:yakitori-sharp" /></template>
<style>
.g9em1k2bk {
  fill: currentColor;
  d: path("m21.075 22.5l-4.325-4.35l-3.55 3.55l-4.225-4.25l1.4-1.4l-1.4-1.425L7.55 16.05L3.325 11.8l1.4-1.4L1.9 7.575L4.025 5.45L1.5 2.9l1.4-1.4l2.55 2.55l2.125-2.125L10.4 4.75l1.425-1.425l4.225 4.25L14.65 9l1.4 1.4l1.425-1.425l4.225 4.25l-3.525 3.525l4.3 4.325z");
}

</style>
