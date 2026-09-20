<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew30400zm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mark-chat-unread-rounded" /></template>
<style>
.ew30400zm {
  fill: currentColor;
  d: path("M17.23 5.73Q16.5 5 16.5 3.963t.73-1.77t1.77-.73t1.77.73t.73 1.77t-.73 1.769t-1.77.73t-1.77-.73M6.078 17l-1.704 1.704q-.379.379-.876.174T3 18.133V4.616q0-.691.463-1.153T4.616 3h9.215q.304 0 .509.233q.204.233.16.536q0 1.048.382 1.914t1.026 1.513q.611.583 1.405.924q.793.342 1.687.342q.258 0 .525-.027t.52-.106q.366-.079.66.117t.295.545v6.394q0 .69-.462 1.153T19.385 17z");
}

</style>
