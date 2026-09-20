<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5170xb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:switch-off" /></template>
<style>
.l5170xb0v {
  fill: currentColor;
  d: path("M17.404 3q.69 0 1.153.463t.462 1.152v14.77q0 .69-.462 1.152T17.404 21H6.616q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3zm-2.096 4.712H8.73v8.557h6.577zm-1 1v4.673H9.73V8.71zm-2.305 9.25q-.29 0-.483.19t-.193.479t.19.484t.48.193t.483-.19t.193-.48t-.19-.483t-.48-.194m.02-13.288q-.29 0-.484.19t-.193.48t.19.483t.48.193t.483-.19t.193-.48t-.19-.483q-.189-.193-.48-.193");
}

</style>
