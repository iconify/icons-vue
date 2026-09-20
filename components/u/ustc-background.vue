<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="utjvgdb0w"/><path fill="url(#SVGDHWlzdmh)" class="nzlysfbmk"/><path fill="url(#SVGrnB4PcyY)" class="mmaqw4b9i"/><path fill="url(#SVGCpc2bdGl)" class="skjqm4bpd"/><path fill="url(#SVGoC2cmeZp)" class="yb7l6jb2y"/></g><defs><linearGradient id="SVGDHWlzdmh" x1="6.382" x2="20.645" y1="17.498" y2="13.694" gradientUnits="userSpaceOnUse"><stop class="rtiaw3bsr"/><stop offset="1" class="ecbqq6bfo"/></linearGradient><linearGradient id="SVGrnB4PcyY" x1="1.716" x2="16.885" y1="9.162" y2="6.019" gradientUnits="userSpaceOnUse"><stop offset=".32" class="jnxbev_9s"/><stop offset=".99" class="fhje0e72v"/></linearGradient><linearGradient id="SVGCpc2bdGl" x1="4.33" x2="20.844" y1="11.997" y2="11.669" gradientUnits="userSpaceOnUse"><stop class="q72m6kbab"/><stop offset="1" class="t4z3efb2r"/></linearGradient><linearGradient id="SVGoC2cmeZp" x1="14.632" x2="19.136" y1="18.293" y2="16.639" gradientUnits="userSpaceOnUse"><stop class="oia-kvpyp"/><stop offset="1" class="uppsi0bzg"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ustc-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.ecbqq6bfo {
  stop-color: var(--svg-color--5599e0, #5599e0);
}

.fhje0e72v {
  stop-color: var(--svg-color--5493f1, #5493f1);
}

.ft5dv1b6b {
  fill: none;
}

.jnxbev_9s {
  stop-color: var(--svg-color--57bc87, #57bc87);
}

.mmaqw4b9i {
  d: path("M8.904 16.953c.07.48 0 2.364-.1 2.524c-.085.005-.255.015-.76-.27a8 8 0 0 1-3.149-3.299a8.05 8.05 0 0 1-.784-5.018q.121-.758.384-1.48c.58.775 1.25 1.475 1.815 2.25q.758 1.083 1.434 2.219c.94 1.61 1.09 2.599 1.16 3.074");
}

.nzlysfbmk {
  d: path("M9.723 6.216c-1 1.52-4.338 2.589-4.888 2.424l-.005-.01q.307-.63.72-1.195a8.1 8.1 0 0 1 2.369-2.169a2.35 2.35 0 0 1 1.1-.3c1.489.03.714 1.235.704 1.25");
}

.oia-kvpyp {
  stop-color: var(--svg-color--58c178, #58c178);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q72m6kbab {
  stop-color: var(--svg-color--58c56e, #58c56e);
}

.rtiaw3bsr {
  stop-color: var(--svg-color--58c07b, #58c07b);
}

.skjqm4bpd {
  d: path("M20 12.2c0 1.05-.2 2.05-.555 2.964c-.945 1.02-7.297-1.495-7.357-1.52c-.87-.384-3.514-1.549-3.749-3.388c-.345-2.64 4.963-4.479 7.298-4.548c.28.005 1.134.014 1.629.42A8.07 8.07 0 0 1 20 12.2");
}

.t4z3efb2r {
  stop-color: var(--svg-color--5492f3, #5492f3);
}

.uppsi0bzg {
  stop-color: var(--svg-color--5493f0, #5493f0);
}

.utjvgdb0w {
  fill: var(--svg-color--183ea4, #183ea4);
  d: path("M7.34 7.382c.348.83.96 1.521 1.74 1.97c1.109.684 5.672-1.91 7.816-3.29c-.444-.52-1.979-1.56-4.573-1.56c-2.599 0-4.173 1.27-4.638 1.91l-.35.97zm7.552 11.58c-.265.12-.925.415-1.234.4c-.37-.01-1.55-.63-2.224-1.804c-.68-1.175-.69-1.95-.14-2.649a10 10 0 0 1 1.764-1.55l5.798.985c.06.33-.135 1.3-1.385 2.6c-1.25 1.284-2.164 1.849-2.469 1.969z");
}

.yb7l6jb2y {
  d: path("M15.702 19.353c-.695.324-1.455.09-1.26-.59c.385-1.305 3.699-2.65 4.433-2.72c.096-.004.13.056.09.126a8.1 8.1 0 0 1-3.263 3.183");
}

</style>
