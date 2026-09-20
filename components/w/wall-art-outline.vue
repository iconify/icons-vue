<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtxuy-bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wall-art-outline" /></template>
<style>
.rtxuy-bnx {
  fill: currentColor;
  d: path("M4.616 21q-.691 0-1.153-.462T3 19.385V8.615q0-.69.463-1.152T4.615 7h4.27L12 3.885L15.116 7h4.269q.69 0 1.153.463T21 8.616v10.769q0 .69-.462 1.153T19.385 21zm0-1h14.769q.23 0 .423-.192t.192-.424V8.616q0-.231-.192-.424T19.385 8H4.615q-.23 0-.423.192T4 8.616v10.769q0 .23.192.423t.423.192M7.5 17.5h9.154l-2.827-3.77l-2.615 3.308l-1.75-2.115zm10.216-4.822q.323-.322.323-.793t-.323-.794t-.793-.322t-.793.322t-.322.793t.322.794t.793.322t.793-.322M10.138 7h3.724L12 5.139zM4 20V8z");
}

</style>
