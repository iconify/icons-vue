<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysnaxebxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shield-card" /></template>
<style>
.ysnaxebxn {
  fill: currentColor;
  d: path("M13 21q-.69 0-1.153-.462t-.462-1.153V15q0-.69.462-1.153T13 13.385h7.385q.69 0 1.153.462T22 15v4.385q0 .69-.462 1.152T20.385 21zm0-1h7.385q.269 0 .442-.173t.173-.442v-2.193h-8.615v2.193q0 .269.173.442T13 20m-.615-3.808H21V15q0-.27-.173-.442q-.173-.173-.442-.173H13q-.27 0-.442.173q-.173.173-.173.442zM5 11.1V5.692l7-2.615l7 2.615V11h-6q-1.708 0-2.854 1.146T9 15v4.312q0 .04.012.08q-1.814-1.403-2.913-3.584T5 11.1");
}

</style>
