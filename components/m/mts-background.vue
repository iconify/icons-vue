<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGlHPOzehx)" class="r4i437pya"/><path class="kus3fw3rv"/><path class="f4rpedcmo"/></g><defs><linearGradient id="SVGlHPOzehx" x1="4.19" x2="19.979" y1="13.212" y2="13.51" gradientUnits="userSpaceOnUse"><stop class="hzibbnuib"/><stop offset="1" class="xmvqffnag"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mts-background" /></template>
<style>
.f4rpedcmo {
  fill: var(--svg-color--fff, #fff);
  d: path("m6.558 5.893l.744 1.666l1.814.193L7.759 8.97l.38 1.788l-1.581-.914l-1.581.914l.38-1.788L4 7.752l1.814-.193z");
}

.ft5dv1b6b {
  fill: none;
}

.hzibbnuib {
  stop-color: var(--svg-color--ffaf02, #ffaf02);
}

.kus3fw3rv {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.278 5.278a6.7 6.7 0 0 1 2.047.314c-1.093 1.989-2.916 3.933-3.718 4.677a.224.224 0 0 0 .304.327c.825-.762 2.72-2.778 3.84-4.847q.586.229 1.106.56c-2.733 4.757-6.998 7.54-9.587 8.704a6.7 6.7 0 0 1-.542-4.525l1.904 1.098l-.515-2.424L9.958 7.5l-1.523-.16a6.7 6.7 0 0 1 4.842-2.06m3.95 1.282c-2.777 4.815-7.086 7.642-9.743 8.847a6.75 6.75 0 0 0 2.634 2.522c1.465-.47 4.028-1.586 5.905-3.382c.21-.202.412-.408.604-.627a.896.896 0 0 1 1.093-1.38a17 17 0 0 0 1.739-3.18a6.74 6.74 0 0 0-2.231-2.8m2.456 3.404a17.4 17.4 0 0 1-1.627 2.88A.895.895 0 0 1 17 14.18c-.215.237-.434.47-.672.694c-1.756 1.68-4.08 2.777-5.626 3.333a6.72 6.72 0 0 0 8.982-8.243");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.xmvqffnag {
  stop-color: var(--svg-color--ff5e1c, #ff5e1c);
}

</style>
