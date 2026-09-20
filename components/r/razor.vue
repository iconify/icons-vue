<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hp3ziy-iu"/><path fill="url(#SVGRa6Kob2L)" class="flec4qhur"/><path fill="url(#SVG2dR8CcDJ)" class="m7hivdg4n"/><path fill="url(#SVGlhur7cMe)" class="pelr-j-8f"/><path fill="url(#SVGJbBuHbVb)" class="n6tqtk3pi"/><path fill="url(#SVGTBKnJcsd)" class="ha0sg25pe"/><path fill="url(#SVG3iTVgc7v)" class="ylmc5wbgs"/><defs><linearGradient id="SVGRa6Kob2L" x1="-152.754" x2="34.365" y1="10.276" y2="10.276" gradientUnits="userSpaceOnUse"><stop class="wwlnv6bzv"/><stop offset="1" class="s5j5scc2s"/></linearGradient><linearGradient id="SVG2dR8CcDJ" x1="-122.798" x2="64.348" y1="11.024" y2="11.024" gradientUnits="userSpaceOnUse"><stop class="wwlnv6bzv"/><stop offset="1" class="s5j5scc2s"/></linearGradient><linearGradient id="SVGlhur7cMe" x1="-92.756" x2="94.27" y1="10.043" y2="10.043" gradientUnits="userSpaceOnUse"><stop class="wwlnv6bzv"/><stop offset="1" class="s5j5scc2s"/></linearGradient><linearGradient id="SVGJbBuHbVb" x1="-62.775" x2="124.252" y1="11.024" y2="11.024" gradientUnits="userSpaceOnUse"><stop class="wwlnv6bzv"/><stop offset="1" class="s5j5scc2s"/></linearGradient><linearGradient id="SVGTBKnJcsd" x1="-32.853" x2="154.294" y1="10.631" y2="10.631" gradientUnits="userSpaceOnUse"><stop class="wwlnv6bzv"/><stop offset="1" class="s5j5scc2s"/></linearGradient><linearGradient id="SVG3iTVgc7v" x1="2.471" x2="19.484" y1="11.051" y2="11.051" gradientUnits="userSpaceOnUse"><stop class="wwlnv6bzv"/><stop offset="1" class="s5j5scc2s"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:razor" /></template>
<style>
.flec4qhur {
  d: path("M17.451 6.822c-.452 0-.817.349-.817.774v8.787c-.011.43.349.785.801.796c.447.011.823-.327.834-.758V7.596c0-.425-.365-.774-.818-.774");
}

.ft5dv1b6b {
  fill: none;
}

.ha0sg25pe {
  d: path("M6.548 5.732c-.452 0-.817.338-.817.752v11.033c0 .415.365.753.817.753c.453 0 .818-.338.818-.753V6.484c0-.414-.365-.752-.818-.752");
}

.hp3ziy-iu {
  fill: var(--svg-color--4fa8ff, #4fa8ff);
  d: path("M20.177 9.001c-.452 0-.817.35-.817.785v4.443c.005.43.381.774.828.769a.8.8 0 0 0 .807-.769V9.786c0-.436-.365-.785-.818-.785");
}

.m7hivdg4n {
  d: path("M14.726 3.005c-.453 0-.818.344-.818.774v16.447c0 .425.365.768.818.768s.817-.343.817-.768V3.779c0-.43-.365-.774-.817-.774");
}

.n6tqtk3pi {
  d: path("M9.274 3.005c-.452 0-.817.344-.817.77V20.23c0 .426.365.769.817.769c.453 0 .818-.343.818-.769V3.77c0-.426-.365-.764-.818-.769z");
}

.pelr-j-8f {
  d: path("M12 7.367c-.453 0-.818.332-.818.747v7.228c0 .409.365.747.818.747s.818-.333.818-.747V8.114c0-.415-.366-.747-.818-.747");
}

.s5j5scc2s {
  stop-color: var(--svg-color--4fa8ff, #4fa8ff);
}

.wwlnv6bzv {
  stop-color: var(--svg-color--14779a, #14779a);
}

.ylmc5wbgs {
  d: path("M3.823 9.001c-.453 0-.818.338-.818.753v4.497c0 .409.365.747.818.747s.817-.338.817-.747V9.754c0-.415-.365-.753-.817-.753");
}

</style>
