<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGpbeK1dxm)" class="qr7cj0c1y"/><path fill="url(#SVGJFw7XbFq)" clip-rule="evenodd" class="czf6llb5z"/><path fill="url(#SVGXM832bEl)" class="so9vw46yp"/><path fill="url(#SVGLigZycBG)" class="upu4lib2e"/><defs><linearGradient id="SVGpbeK1dxm" x1="11.831" x2="11.831" y1="20.285" y2="13.715" gradientUnits="userSpaceOnUse"><stop offset=".59" class="nd2xe-t1t"/><stop offset="1" class="vqadd0zuh"/></linearGradient><linearGradient id="SVGJFw7XbFq" x1="12" x2="12" y1="9.41" y2="15.233" gradientUnits="userSpaceOnUse"><stop offset=".57" class="o2dkrib9y"/><stop offset="1" class="y48o4db6v"/></linearGradient><linearGradient id="SVGXM832bEl" x1="8.595" x2="11.623" y1="9.993" y2="4.419" gradientUnits="userSpaceOnUse"><stop offset=".46" class="gcb-jtbke"/><stop offset="1" class="b1w_4jb7m"/></linearGradient><linearGradient id="SVGLigZycBG" x1="15.403" x2="12.375" y1="9.993" y2="4.419" gradientUnits="userSpaceOnUse"><stop offset=".26" class="lpiouh0nc"/><stop offset="1" class="b1w_4jb7m"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:slg" /></template>
<style>
.b1w_4jb7m {
  stop-color: var(--svg-color--d8f3fc, #d8f3fc);
}

.czf6llb5z {
  fill-rule: evenodd;
  d: path("M11.99 15.234A960 960 0 0 0 6.176 12.3l5.812-2.89l5.834 2.89zm0-.916c-1.308-.662-3.94-1.996-3.987-2.012l3.986-1.98l4.008 1.985l-4.008 2.012zm-1.843-1.525l1.853.794l1.853-.8L12 12l-1.853.789z");
}

.ft5dv1b6b {
  fill: none;
}

.gcb-jtbke {
  stop-color: var(--svg-color--70b8c7, #70b8c7);
}

.lpiouh0nc {
  stop-color: var(--svg-color--96cedf, #96cedf);
}

.nd2xe-t1t {
  stop-color: var(--svg-color--a9cfd8, #a9cfd8);
}

.o2dkrib9y {
  stop-color: var(--svg-color--d7fdff, #d7fdff);
}

.qr7cj0c1y {
  d: path("m3.53 17.225l2.647-4.923l5.876 2.583l5.77-2.583l2.647 4.923L12.053 21z");
}

.so9vw46yp {
  d: path("M11.999 11.47L7.764 9.607L11.999 3z");
}

.upu4lib2e {
  d: path("m12 11.47l4.235-1.863L12 3z");
}

.vqadd0zuh {
  stop-color: var(--svg-color--cfe6ee, #cfe6ee);
}

.y48o4db6v {
  stop-color: var(--svg-color--dafbff, #dafbff);
}

</style>
