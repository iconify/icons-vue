<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g81z2n1-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settings-power-outline-rounded" /></template>
<style>
.g81z2n1-j {
  fill: currentColor;
  d: path("M11.5 11.5V4.154q0-.213.143-.357q.143-.143.357-.143t.357.143t.143.357V11.5q0 .214-.143.357T12 12t-.357-.143t-.143-.357M12 18q-2.927 0-4.963-2.036T5 11q0-1.642.716-3.071q.717-1.429 1.98-2.439q.177-.146.406-.153q.229-.006.4.165q.16.16.113.358q-.048.198-.219.338q-1.104.87-1.75 2.125Q6 9.579 6 11q0 2.5 1.75 4.25T12 17t4.25-1.75T18 11q0-1.44-.637-2.696t-1.76-2.106q-.17-.14-.208-.348t.103-.348q.171-.171.4-.174t.406.163q1.244 1.048 1.97 2.467T19 11q0 2.927-2.036 4.964T12 18m-4 5.77q-.31 0-.54-.23T7.23 23t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23m4 0q-.31 0-.54-.23t-.23-.54t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23m4 0q-.31 0-.54-.23t-.23-.54t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23");
}

</style>
