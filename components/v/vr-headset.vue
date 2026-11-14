<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6qehna_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:vr-headset" /></template>
<style>
.u6qehna_w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 6.25h13q3.75 0 3.75 3.75v5q0 3.75-3.75 3.75h-3q-.097 0-.191-.025q-.094-.024-.179-.072t-.154-.116t-.119-.151l-1.488-2.481q-.238-.33-1.369-.33t-1.369.33l-1.488 2.481q-.05.083-.119.151q-.07.068-.154.116q-.085.048-.179.072q-.094.025-.191.025h-3q-3.75 0-3.75-3.75v-5q0-3.75 3.75-3.75");
}

</style>
