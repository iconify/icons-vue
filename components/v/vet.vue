<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGJKDrmbyQ)" class="d7ognibpy"/><defs><linearGradient id="SVGJKDrmbyQ" x1="3" x2="20.048" y1="20.593" y2="1.144" gradientUnits="userSpaceOnUse"><stop class="l1p8ypbhf"/><stop offset=".15" class="dux3_ebyy"/><stop offset=".47" class="x-pclcc3l"/><stop offset=".74" class="hfiv3eb5b"/><stop offset="1" class="r3he05rto"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vet" /></template>
<style>
.d7ognibpy {
  d: path("M21 3.844h-1.609c-.394 0-.748.225-.922.58l-4.219 8.74l-.006-.005l-1.125 2.328v.012l-1.125 2.329l-5.619-11.65h1.603c.394 0 .754.225.923.58l3.673 7.554l1.125-2.329l-2.965-6.103a3.61 3.61 0 0 0-3.25-2.036H3l1.125 2.334l6.75 13.978h2.25z");
}

.dux3_ebyy {
  stop-color: var(--svg-color--4163ad, #4163ad);
}

.ft5dv1b6b {
  fill: none;
}

.hfiv3eb5b {
  stop-color: var(--svg-color--54b1b6, #54b1b6);
}

.l1p8ypbhf {
  stop-color: var(--svg-color--582974, #582974);
}

.r3he05rto {
  stop-color: var(--svg-color--86e931, #86e931);
}

.x-pclcc3l {
  stop-color: var(--svg-color--22b2f9, #22b2f9);
}

</style>
