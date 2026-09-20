<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG3fo0abJU)" clip-rule="evenodd" class="gfa7txbnx"/><path fill="url(#SVGTFzSPcdz)" clip-rule="evenodd" class="rq95lhb9h"/><path fill="url(#SVGTRqMzbVX)" clip-rule="evenodd" class="zs7qr6bor"/><defs><linearGradient id="SVG3fo0abJU" x1="2.91" x2="21.09" y1="12.235" y2="12" gradientUnits="userSpaceOnUse"><stop class="slsok2bjq"/><stop offset="1" class="jstn7jpqh"/></linearGradient><linearGradient id="SVGTFzSPcdz" x1="21.251" x2="2.747" y1="11.999" y2="11.999" gradientUnits="userSpaceOnUse"><stop class="sew99jyoe"/><stop offset="1" class="cm54zuj5t"/></linearGradient><linearGradient id="SVGTRqMzbVX" x1="3" x2="21" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="sew99jyoe"/><stop offset="1" class="cm54zuj5t"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rgt" /></template>
<style>
.cm54zuj5t {
  stop-color: var(--svg-color--f0f0f0, #f0f0f0);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gfa7txbnx {
  fill-rule: evenodd;
  d: path("M12 17.294a5.294 5.294 0 1 0 0-10.588a5.294 5.294 0 0 0 0 10.588m0-.53a4.765 4.765 0 1 0 0-9.53a4.765 4.765 0 0 0 0 9.53");
}

.jstn7jpqh {
  stop-color: var(--svg-color--f9f9f9, #f9f9f9);
  stop-opacity: 0;
}

.rq95lhb9h {
  fill-rule: evenodd;
  d: path("M8.56 17.962a6.882 6.882 0 1 0 6.883-11.92a6.882 6.882 0 0 0-6.883 11.92m3.44.391a6.353 6.353 0 1 0 0-12.706a6.353 6.353 0 0 0 0 12.706");
}

.sew99jyoe {
  stop-color: var(--svg-color--f0f0f0, #f0f0f0);
}

.slsok2bjq {
  stop-color: var(--svg-color--f9f9f9, #f9f9f9);
}

.zs7qr6bor {
  fill-rule: evenodd;
  d: path("M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18m0-.53A8.47 8.47 0 0 0 20.47 12A8.47 8.47 0 0 0 12 3.53A8.47 8.47 0 0 0 3.53 12A8.47 8.47 0 0 0 12 20.47");
}

</style>
