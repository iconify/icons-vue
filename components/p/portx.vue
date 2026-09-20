<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ihv-icb_u"/><path clip-rule="evenodd" class="rce0hdb8h"/><path fill="url(#SVGgnIPxdqd)" class="a1c82pbgt"/><path clip-rule="evenodd" class="f7yrit3ku"/><defs><linearGradient id="SVGgnIPxdqd" x1="12.244" x2="3" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:portx" /></template>
<style>
.a1c82pbgt {
  d: path("M12.6 16.2a4.2 4.2 0 1 1 0-8.401a4.2 4.2 0 0 1 0 8.4");
}

.f7yrit3ku {
  fill: var(--svg-color--2ff6d3, #2ff6d3);
  fill-rule: evenodd;
  d: path("M13.806 17.85c.798 1.5 1.698 2.04 2.394 2.04s1.596-.54 2.394-2.04c.768-1.44 1.278-3.504 1.278-5.85c0-2.34-.51-4.41-1.278-5.85c-.798-1.5-1.698-2.04-2.394-2.04s-1.596.54-2.394 2.04c-.768 1.44-1.278 3.504-1.278 5.85c0 2.34.51 4.41 1.278 5.85M11.4 12c0 4.968 2.148 9 4.8 9s4.8-4.032 4.8-9s-2.148-9-4.8-9s-4.8 4.032-4.8 9");
}

.ft5dv1b6b {
  fill: none;
}

.ihv-icb_u {
  fill: var(--svg-color--2ff6d3, #2ff6d3);
  fill-rule: evenodd;
  d: path("M5.406 17.85c.798 1.5 1.698 2.04 2.394 2.04s1.596-.54 2.394-2.04c.768-1.44 1.278-3.504 1.278-5.85c0-2.34-.51-4.41-1.278-5.85c-.798-1.5-1.698-2.04-2.394-2.04s-1.596.54-2.394 2.04C4.638 7.59 4.128 9.654 4.128 12c0 2.34.51 4.41 1.278 5.85M3 12c0 4.968 2.148 9 4.8 9s4.8-4.032 4.8-9s-2.148-9-4.8-9S3 7.032 3 12");
}

.rce0hdb8h {
  fill: var(--svg-color--2ff6d3, #2ff6d3);
  fill-rule: evenodd;
  d: path("M9.606 17.85c.798 1.5 1.698 2.04 2.394 2.04s1.596-.54 2.394-2.04c.768-1.44 1.278-3.504 1.278-5.85c0-2.34-.51-4.41-1.278-5.85c-.798-1.5-1.698-2.04-2.394-2.04s-1.596.54-2.394 2.04C8.838 7.59 8.328 9.654 8.328 12c0 2.34.51 4.41 1.278 5.85M7.2 12c0 4.968 2.148 9 4.8 9s4.8-4.032 4.8-9s-2.148-9-4.8-9s-4.8 4.032-4.8 9");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

</style>
