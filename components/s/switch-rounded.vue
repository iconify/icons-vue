<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oje4zcb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:switch-rounded" /></template>
<style>
.oje4zcb_h {
  fill: currentColor;
  d: path("M6.616 21q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3h10.788q.69 0 1.153.463t.462 1.153v14.769q0 .69-.462 1.153T17.404 21zm2.903-4.711h4.959q.35 0 .58-.233q.23-.232.23-.575V8.539q0-.344-.232-.576t-.575-.232H9.522q-.35 0-.58.232t-.23.576v6.942q0 .343.232.575t.575.233m.193-1v-4.673h4.577v4.673zm2.285-9.25q.29 0 .483-.19t.193-.48t-.19-.483t-.48-.194t-.483.19t-.193.48t.19.483t.48.194m0 13.288q.29 0 .483-.19t.193-.48t-.19-.483t-.48-.193t-.483.19t-.193.48t.19.483t.48.193");
}

</style>
