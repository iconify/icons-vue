<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vonynvb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stacked-line-chart-rounded" /></template>
<style>
.vonynvb7m {
  fill: currentColor;
  d: path("m3.135 19.635l5.306-5.306q.459-.46 1.136-.46t1.137.46l2.401 2.402q.193.192.462.183q.27-.01.442-.222l6.208-7.128q.14-.172.338-.172q.197 0 .362.147q.14.14.153.326q.012.185-.128.35l-6.206 7.166q-.46.535-1.155.562q-.697.028-1.206-.481l-2.366-2.366q-.173-.173-.442-.173t-.442.173l-5.27 5.27q-.151.151-.355.161t-.375-.161T2.964 20t.17-.365m0-6l5.307-5.306q.459-.46 1.136-.46t1.137.46l2.402 2.402q.192.192.461.183q.27-.01.442-.222l6.208-7.128q.14-.172.338-.172q.197 0 .362.147q.14.14.153.326q.012.185-.128.35l-6.206 7.166q-.46.535-1.155.562q-.697.028-1.206-.481l-2.366-2.366q-.173-.173-.442-.173t-.442.173l-5.27 5.27q-.151.151-.355.161t-.375-.161T2.964 14t.17-.365");
}

</style>
