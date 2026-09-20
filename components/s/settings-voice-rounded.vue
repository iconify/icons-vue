<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d58c8ccer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settings-voice-rounded" /></template>
<style>
.d58c8ccer {
  fill: currentColor;
  d: path("M7.46 23.54q-.23-.23-.23-.54t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23t-.54-.23m4.54.23q-.31 0-.54-.23t-.23-.54t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23m3.46-.23q-.23-.23-.23-.54t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23t-.54-.23m-4.883-11.117Q10 11.846 10 11V5q0-.846.577-1.423T12 3t1.423.577T14 5v6q0 .846-.577 1.423T12 13t-1.423-.577M11.5 20v-2.985q-2.165-.223-3.716-1.752t-1.748-3.738q-.03-.214.11-.37Q6.286 11 6.5 11t.357.153t.185.366q.197 1.923 1.623 3.202T12 16q1.935 0 3.348-1.291q1.413-1.292 1.61-3.19q.042-.213.185-.366T17.5 11t.354.156t.11.369q-.197 2.179-1.735 3.723T12.5 17.015V20q0 .214-.143.357T12 20.5t-.357-.143T11.5 20");
}

</style>
