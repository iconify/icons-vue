<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGtM3JidPE)" clip-rule="evenodd" class="gx1ipacwo"/><defs><linearGradient id="SVGtM3JidPE" x1="15.14" x2="5.642" y1="4.273" y2="17.272" gradientUnits="userSpaceOnUse"><stop class="q94r0s-nq"/><stop offset="1" class="k4ntd84as"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tfuel" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gx1ipacwo {
  fill-rule: evenodd;
  d: path("M12.39 21c-2.295-.45-6.845-2.493-6.692-7.038h.01c-.046-.9.368-3.163 2.389-4.995c2.529-2.29 3.1-3.056 2.997-5.967c.922.54 2.767 2.165 2.812 4.32a8.2 8.2 0 0 1-.387 2.137c-.364 1.071.239 1.971 1.139 2.016c.909.041 1.575-.589 1.633-1.7c.72.72 2.133 2.664 2.007 4.698c-.162 2.542-1.426 3.45-2.214 3.933c-.242.149-.565.271-.922.407c-.968.367-2.19.831-2.773 2.189m3.627-15.957v.648c-.005.108-.104.418-.45.77c-.342.355-.428.9-.428 1.124A1.55 1.55 0 0 0 16.2 9.066c.116-.313.325-.583.598-.774c.36-.198.37-.639.36-.855a4.3 4.3 0 0 0-1.142-2.394M8.398 12.45v1.8h2.7v3.15h1.8v-3.15h2.7v-1.8z");
}

.k4ntd84as {
  stop-color: var(--svg-color--f2a23e, #f2a23e);
}

.q94r0s-nq {
  stop-color: var(--svg-color--ee6833, #ee6833);
}

</style>
