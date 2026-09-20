<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGVfA7cbiU)" class="b6p1u0gjf"/><path fill="url(#SVGF2dBIdPh)" class="t9px-eb_y"/><defs><linearGradient id="SVGVfA7cbiU" x1="2.992" x2="19.676" y1="8.88" y2="10.573" gradientUnits="userSpaceOnUse"><stop class="xa-hxfbxg"/><stop offset=".82" class="dup7kxhwp"/><stop offset="1" class="cmh4pjbiz"/></linearGradient><linearGradient id="SVGF2dBIdPh" x1="5.671" x2="18.921" y1="7.289" y2="10.134" gradientUnits="userSpaceOnUse"><stop class="xa-hxfbxg"/><stop offset=".72" class="j0x8w7bxa"/><stop offset="1" class="cmh4pjbiz"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zbc" /></template>
<style>
.b6p1u0gjf {
  d: path("M3.347 13.163c-.795-.86-.125-2.26 1.025-2.16l15.48 1.375c1.01.09 1.505 1.3.855 2.1l-2.905 3.56l-.325-.275l.32.275a1.25 1.25 0 0 1-.96.46h-8.04c-.35 0-.68-.15-.915-.405l-4.535-4.935zm.95-1.3c-.38-.035-.6.43-.34.715l4.535 4.935a.42.42 0 0 0 .305.135h8.04c.12 0 .24-.055.32-.15l2.91-3.565c.215-.265.05-.67-.285-.7L4.297 11.858z");
}

.cmh4pjbiz {
  stop-color: var(--svg-color--6a66b2, #6a66b2);
}

.dup7kxhwp {
  stop-color: var(--svg-color--a274bf, #a274bf);
}

.ft5dv1b6b {
  fill: none;
}

.j0x8w7bxa {
  stop-color: var(--svg-color--a991cb, #a991cb);
}

.t9px-eb_y {
  d: path("M6.241 6.754c.245-.895 1.23-1.435 2.19-1.195l9.586 2.405a1.26 1.26 0 0 1 .985 1.2v.1c0 .735-.685 1.31-1.476 1.235l-9.935-.995c-1.075-.105-1.8-1.07-1.535-2.05zm1.955-.395c-.48-.12-.97.15-1.09.6l-.19.7c-.13.49.23.97.77 1.025l9.935.99c.26.025.49-.165.49-.41v-.1c0-.19-.134-.35-.33-.4l-9.585-2.4z");
}

.xa-hxfbxg {
  stop-color: var(--svg-color--45c1cb, #45c1cb);
}

</style>
