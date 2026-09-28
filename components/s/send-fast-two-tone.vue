<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kb_joubbb"/><path class="p1zmq2b4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:send-fast-two-tone" /></template>
<style>
.kb_joubbb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22.9589 2.2837L18.4511 17.5197C18.1997 18.3694 17.4193 18.9523 16.5332 18.9523C15.8723 18.9523 15.2541 18.6258 14.8815 18.08L11.4582 13.0658C11.3177 12.86 11.14 12.6823 10.9342 12.5418L5.92 9.1185C5.3742 8.7459 5.0477 8.1277 5.0477 7.4668C5.0477 6.5807 5.6306 5.8003 6.4803 5.5489L21.7163 1.0411C21.8084 1.0138 21.9039 1 22 1C22.5523 1 23 1.4477 23 2C23 2.0961 22.9862 2.1916 22.9589 2.2837Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p1zmq2b4z {
  d: path("M22 2L17.4921 17.236C17.3665 17.6608 16.9762 17.9523 16.5332 17.9523C16.2028 17.9523 15.8937 17.7891 15.7074 17.5162L12.2841 12.502C12.0733 12.1933 11.8067 11.9267 11.498 11.7159L6.4838 8.2926C6.2109 8.1063 6.0477 7.7972 6.0477 7.4668C6.0477 7.0238 6.3392 6.6335 6.764 6.5079L22 2ZM11.9652 12.0348L22 2M2 22L6.5 17.5M2 16L5.5 12.5M8 22L11.5 18.5");
}

</style>
