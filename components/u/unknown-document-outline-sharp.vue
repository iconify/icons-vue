<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt_crt3pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:unknown-document-outline-sharp" /></template>
<style>
.rt_crt3pl {
  fill: currentColor;
  d: path("M5 4v6.366v-.058V20zv4zm2.5 9.5h3.271q.16-.261.34-.514t.373-.486H7.5zm0 4h2.454q-.031-.25-.031-.49t.012-.51H7.5zM4 21V3h9.5L18 7.5v3.05q-.27-.067-.51-.116q-.24-.05-.49-.068V8h-4V4H5v16h5.848q.16.287.34.537t.393.463zm15.143-7.143q1.165 1.164 1.165 2.835t-1.165 2.836t-2.835 1.164t-2.836-1.164t-1.164-2.836q0-1.67 1.164-2.835q1.165-1.165 2.836-1.165t2.835 1.165m-2.46 5.523q.16-.159.16-.376q0-.218-.16-.376q-.158-.159-.375-.159t-.376.159t-.159.376t.159.376t.376.158t.376-.158m-.75-1.626h.747v-.173q0-.295.15-.478q.15-.184.35-.384q.35-.3.55-.613t.2-.775q0-.687-.446-1.124t-1.177-.438q-.537 0-1 .338t-.662.874l.685.273q.113-.3.37-.525t.607-.225q.413 0 .645.207q.232.206.232.62q0 .294-.17.491q-.169.197-.369.397q-.15.15-.293.32q-.143.169-.268.33q-.075.131-.113.29q-.037.16-.037.322z");
}

</style>
