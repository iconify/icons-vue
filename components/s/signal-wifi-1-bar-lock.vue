<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpa4zjbgw"/><path class="bxixdwdoe"/><path class="niufhab5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:signal-wifi-1-bar-lock" /></template>
<style>
.bxixdwdoe {
  fill: currentColor;
  d: path("M15.5 14.5c0-2.8 2.2-5 5-5c.4 0 .7 0 1 .1L23.6 7c-.4-.3-4.9-4-11.6-4S.8 6.7.4 7L12 21.5l3.5-4.3z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.niufhab5x {
  fill: currentColor;
  d: path("m6.7 14.9l5.3 6.6l3.5-4.3v-2.6c0-.2 0-.5.1-.7c-.9-.5-2.2-.9-3.6-.9c-3 0-5.1 1.7-5.3 1.9");
}

.xpa4zjbgw {
  fill: currentColor;
  d: path("M23 16v-1.5c0-1.4-1.1-2.5-2.5-2.5S18 13.1 18 14.5V16c-.5 0-1 .5-1 1v4c0 .5.5 1 1 1h5c.5 0 1-.5 1-1v-4c0-.5-.5-1-1-1m-1 0h-3v-1.5c0-.8.7-1.5 1.5-1.5s1.5.7 1.5 1.5z");
}

</style>
