<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGza5kDPYD)" class="u80ufupwe"/><path fill="url(#SVGhOZWl7Ls)" class="xw4too5vr"/><defs><linearGradient id="SVGza5kDPYD" x1="6.448" x2="6.448" y1="7.726" y2="16.274" gradientUnits="userSpaceOnUse"><stop class="fi71a7btv"/><stop offset="1" class="g7ask0mfb"/></linearGradient><linearGradient id="SVGhOZWl7Ls" x1="15.6" x2="15.6" y1="9.974" y2="14.474" gradientUnits="userSpaceOnUse"><stop class="fi71a7btv"/><stop offset="1" class="g7ask0mfb"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mex" /></template>
<style>
.fi71a7btv {
  stop-color: var(--svg-color--213973, #213973);
}

.ft5dv1b6b {
  fill: none;
}

.g7ask0mfb {
  stop-color: var(--svg-color--02094b, #02094b);
}

.u80ufupwe {
  d: path("m5.718 8.31l.901-.584l.847.583l-.847.515zm-1.53.847l-.9.584l.9.514l.847-.514zM3 9.974v4.218l3.6 2.082V12.11zm3.62-.817l-.902.584l.901.514l.847-.514zm-.902 2.016l.901-.584l.847.583l-.847.515zm-.329-1.295l-.9.583l.9.515l.848-.515zm1.532.583l.901-.583l.847.583l-.847.515zm2.13-1.304l-.902.584l.901.514l.847-.514z");
}

.xw4too5vr {
  d: path("M10.2 14.474v-4.5h.9l1.35 2.986l1.35-2.986h3.15v.9h-2.26v.9h2.26v.9h-2.26v.9h2.26v.617l1.402-2.057l-1.4-2.16h1.096l.862 1.344l.822-1.344h1.177l-1.42 2.16l1.51 2.34h-1.135l-.954-1.514l-.944 1.514H13.8v-2.34l-.9 2.34H12l-.9-2.34v2.34z");
}

</style>
