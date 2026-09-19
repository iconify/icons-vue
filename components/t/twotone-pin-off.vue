<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kj0wqobnp"/><path class="x2jnnpeye"/><path class="nmhw6dbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-pin-off" /></template>
<style>
.kj0wqobnp {
  fill: currentColor;
  d: path("M9.644 12.184L11.461 14H8v-.172zM13 4v6.46l-.73-.73L11 8.46V4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.nmhw6dbmm {
  fill: currentColor;
  d: path("M2.27 2.27L1 3.54L20.46 23l1.27-1.27L11 11z");
}

.x2jnnpeye {
  fill: currentColor;
  d: path("m9 9l1.914 1.914L8 13.828V14h6l2 2h-3v4l-1 3l-1-3v-4H6v-3l3-3zm8-7v2l-2 1v5l3 3v2.461l-5-5.001V4h-2v4.46l-2-2V5L7 4V2z");
}

</style>
