<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihyc3bcue"/><path class="hnrjzkb2q"/><path class="xietzojdi"/><path class="bn6ebpb5p"/><path class="bpzm4jenn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-20mp" /></template>
<style>
.bn6ebpb5p {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5V5h14z");
}

.bpzm4jenn {
  fill: currentColor;
  d: path("M14 11.5h2.5c.55 0 1-.45 1-1v-4c0-.55-.45-1-1-1H14c-.55 0-1 .45-1 1v4c0 .55.45 1 1 1m.5-4.5H16v3h-1.5zM11 10H8V9h2c.55 0 1-.45 1-1V6.5c0-.55-.45-1-1-1H6.5V7h3v1h-2c-.55 0-1 .45-1 1v2.5H11z");
}

.hnrjzkb2q {
  fill: currentColor;
  d: path("M14.5 7H16v3h-1.5zm.5 7h1.5v1.5H15z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ihyc3bcue {
  fill: currentColor;
  d: path("M5 19h14V5H5zm13-5.5V16c0 .55-.45 1-1 1h-2v1.5h-1.5v-6H17c.55 0 1 .45 1 1m-5-7c0-.55.45-1 1-1h2.5c.55 0 1 .45 1 1v4c0 .55-.45 1-1 1H14c-.55 0-1-.45-1-1zM6.5 9c0-.55.45-1 1-1h2V7h-3V5.5H10c.55 0 1 .45 1 1V8c0 .55-.45 1-1 1H8v1h3v1.5H6.5zM6 13.5c0-.55.45-1 1-1h4.5c.55 0 1 .45 1 1v5H11V14h-1v3H8.5v-3h-1v4.5H6z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.xietzojdi {
  fill: currentColor;
  d: path("M7.5 14h1v3H10v-3h1v4.5h1.5v-5c0-.55-.45-1-1-1H7c-.55 0-1 .45-1 1v5h1.5zm6-1.5v6H15V17h2c.55 0 1-.45 1-1v-2.5c0-.55-.45-1-1-1zm3 3H15V14h1.5z");
}

</style>
