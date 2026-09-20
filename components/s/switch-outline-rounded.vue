<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e60bw83fj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:switch-outline-rounded" /></template>
<style>
.e60bw83fj {
  fill: currentColor;
  d: path("M6.616 21q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3h10.788q.69 0 1.153.463t.462 1.153v14.769q0 .69-.462 1.153T17.404 21zm0-1h10.788q.269 0 .442-.173t.173-.442V4.615q0-.269-.173-.442T17.404 4H6.616q-.27 0-.452.173q-.183.173-.183.443v14.769q0 .269.183.442q.182.173.452.173m2.903-3.712h4.959q.35 0 .58-.232t.23-.575V8.539q0-.344-.232-.576t-.575-.232H9.522q-.35 0-.58.232t-.23.576v6.942q0 .343.232.575t.575.233m.193-1v-4.673h4.577v4.673zm2.285-8.75q.29 0 .483-.19t.193-.48t-.19-.483t-.48-.194t-.483.19t-.193.48t.19.483t.48.194m0 12.288q.29 0 .483-.19t.193-.48t-.19-.492t-.48-.203t-.483.203t-.193.493t.19.48t.48.189M12 12");
}

</style>
