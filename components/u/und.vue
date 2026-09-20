<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG3Ka5pcVx)" class="jnjre8v6f"/><path fill="url(#SVGoijG1chE)" class="twuwfe92l"/><path fill="url(#SVGijRHTcXR)" class="dvhp40z7x"/><path fill="url(#SVGJLf9Cb4s)" class="rwjjy7bfc"/><defs><linearGradient id="SVG3Ka5pcVx" x1="12.003" x2="12.003" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="al32kp7ym"/><stop offset="1" class="ffke88bnl"/></linearGradient><linearGradient id="SVGoijG1chE" x1="18.444" x2="16.269" y1="3.782" y2="20.774" gradientUnits="userSpaceOnUse"><stop class="bgg0ytblm"/><stop offset="1" class="gyxjo0bdu"/></linearGradient><linearGradient id="SVGijRHTcXR" x1="11.992" x2="11.992" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="y977h66az"/><stop offset="1" class="xb1ftnbyp"/></linearGradient><linearGradient id="SVGJLf9Cb4s" x1="9.39" x2="9.39" y1="3.782" y2="17.867" gradientUnits="userSpaceOnUse"><stop class="u_jcfacwa"/><stop offset="1" class="omv1ki9pt"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:und" /></template>
<style>
.al32kp7ym {
  stop-color: var(--svg-color--a41351, #a41351);
}

.bgg0ytblm {
  stop-color: var(--svg-color--aa1654, #aa1654);
}

.dvhp40z7x {
  d: path("M3.563 13.176V3l2.413.788v9c0 3.751 2.677 4.95 4.016 5.079c-.641.315-1.873.394-2.413.394c-3.212 0-4.016-3.392-4.016-5.085");
}

.ffke88bnl {
  stop-color: var(--svg-color--e0196c, #e0196c);
}

.ft5dv1b6b {
  fill: none;
}

.gyxjo0bdu {
  stop-color: var(--svg-color--e51970, #e51970);
}

.jnjre8v6f {
  d: path("M20.437 13.958V3c-3.859 0-4.82 3.133-4.82 4.697v5.867c0 4.697-5.896 5.872-8.843 5.872C9.024 20.685 11.465 21 12.399 21c6.43 0 8.038-4.697 8.038-7.042");
}

.omv1ki9pt {
  stop-color: var(--svg-color--0264eb, #0264eb);
}

.rwjjy7bfc {
  d: path("M8.383 6.915c0-2.193-1.609-3.003-2.407-3.133v9.394c0 3.91 2.407 4.691 3.61 4.691c1.447 0 2.684-.782 3.218-1.17c-3.538.625-4.42-2.087-4.42-3.52z");
}

.twuwfe92l {
  d: path("M20.438 3c-1.086.652-2.413 1.946-2.413 3.915v6.26c0 2.217-1.125 6.65-5.625 6.65c-2.571 0-4.388-.17-5.575-.366A12.9 12.9 0 0 0 12.394 21c6.435 0 8.044-4.697 8.044-7.042z");
}

.u_jcfacwa {
  stop-color: var(--svg-color--133bc1, #133bc1);
}

.xb1ftnbyp {
  stop-color: var(--svg-color--025de1, #025de1);
}

.y977h66az {
  stop-color: var(--svg-color--1631b6, #1631b6);
}

</style>
