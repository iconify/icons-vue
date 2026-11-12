<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s_w074bqo"/><path class="glsnqibje"/><path class="b6ykzlr9k"/><path class="yod4tl2uo"/><path class="ejaksrbvy"/><path class="pr1jznbmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sleeping-circle-linear" /></template>
<style>
.b6ykzlr9k {
  d: path("M13.5 11C14.0669 11.6303 14.7564 12 15.5 12C16.2436 12 16.9331 11.6303 17.5 11");
}

.ejaksrbvy {
  stroke-linejoin: round;
  d: path("M14.0479 5.5L15.7799 6.5L13.0479 7.23205L14.7799 8.23205");
}

.glsnqibje {
  d: path("M6.5 11C7.06692 11.6303 7.75638 12 8.5 12C9.24362 12 9.93308 11.6303 10.5 11");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pr1jznbmm {
  stroke-linejoin: round;
  d: path("M12 16H12.0001");
}

.s_w074bqo {
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2");
}

.yod4tl2uo {
  stroke-linejoin: round;
  d: path("M17 4L20.4641 2L19 7.4641L22.4641 5.4641");
}

</style>
