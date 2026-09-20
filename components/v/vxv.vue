<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGd6yalboL)" clip-rule="evenodd" class="zpo86mb8h"/><path fill="url(#SVGQnIjQeuq)" clip-rule="evenodd" class="h0i9xubmx"/><path fill="url(#SVGnLUard3o)" class="nrt1eqbgr"/><path fill="url(#SVGnXSYJeTr)" class="k-e0inbbc"/><defs><linearGradient id="SVGd6yalboL" x1="8.345" x2="16.128" y1="5.048" y2="18.714" gradientUnits="userSpaceOnUse"><stop class="oljlq8oco"/><stop offset="1" class="y77mn86yk"/></linearGradient><linearGradient id="SVGQnIjQeuq" x1="4.731" x2="20.464" y1="12.805" y2="9.474" gradientUnits="userSpaceOnUse"><stop class="rc81itbxf"/><stop offset="1" class="s56ft8t5h"/></linearGradient><linearGradient id="SVGnLUard3o" x1="18.001" x2="1.441" y1="2.766" y2="11.938" gradientUnits="userSpaceOnUse"><stop class="eyit18b8a"/><stop offset=".334" class="xhtmbbbli"/><stop offset=".597" class="xhtmbbbli"/><stop offset="1" class="uxhoz6b3s"/></linearGradient><linearGradient id="SVGnXSYJeTr" x1="10.908" x2="14.325" y1="10.79" y2="12.769" gradientUnits="userSpaceOnUse"><stop class="kkwo7kttf"/><stop offset="1" class="boqtksn7k"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vxv" /></template>
<style>
.boqtksn7k {
  stop-color: var(--svg-color--6ea9b4, #6ea9b4);
}

.eyit18b8a {
  stop-color: var(--svg-color--6aa4ae, #6aa4ae);
}

.ft5dv1b6b {
  fill: none;
}

.h0i9xubmx {
  fill-rule: evenodd;
  d: path("m12.313 17.879l5.419-9.268c.221-.378-.204-.802-.587-.585l-5.13 2.912l-5.116-2.91c-.382-.218-.808.206-.588.584l5.405 9.267a.346.346 0 0 0 .597 0m-.023-1.617l3.422-6.042c.086-.151-.084-.318-.236-.232l-3.478 1.983l.007.018l-2.084 1.188l1.77 3.086c.132.232.468.23.6-.001m-2.818-3.867l1.638-.93l-2.692-1.554c-.152-.088-.323.08-.236.232z");
}

.k-e0inbbc {
  d: path("m10.57 11.155l3.575 2.06l.601-.654l-3.531-2.076z");
}

.kkwo7kttf {
  stop-color: var(--svg-color--639ca3, #639ca3);
}

.nrt1eqbgr {
  d: path("m11.73 12.145l-.891-.522l1.366-.793l.86.53z");
}

.oljlq8oco {
  stop-color: var(--svg-color--dcdcdc, #dcdcdc);
}

.rc81itbxf {
  stop-color: var(--svg-color--51898a, #51898a);
}

.s56ft8t5h {
  stop-color: var(--svg-color--7db9c9, #7db9c9);
}

.uxhoz6b3s {
  stop-color: var(--svg-color--629ca3, #629ca3);
}

.xhtmbbbli {
  stop-color: var(--svg-color--538289, #538289);
}

.y77mn86yk {
  stop-color: var(--svg-color--585858, #585858);
}

.zpo86mb8h {
  fill-rule: evenodd;
  d: path("M19.562 7.758L12 3.504L4.438 7.758v8.484L12 20.496l7.562-4.254zm-7.315-4.693a.5.5 0 0 0-.494 0L4.19 7.318a.5.5 0 0 0-.257.44v8.484c0 .182.098.35.257.44l7.562 4.253a.5.5 0 0 0 .494 0l7.562-4.253a.5.5 0 0 0 .257-.44V7.758a.5.5 0 0 0-.257-.44z");
}

</style>
