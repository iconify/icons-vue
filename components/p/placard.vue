<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="lk_t5gbym"/><path class="cld7oibet"/><linearGradient id="SVGhE3R7cRd" x1="66" x2="66" y1="46.374" y2="31.354" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="a72as_i6q"/><stop offset=".944" class="ptnuqol_c"/></linearGradient><path fill="url(#SVGhE3R7cRd)" class="cerf30bmr"/><linearGradient id="SVGgJ6I3bao" x1="66" x2="66" y1="127.993" y2="114.523" gradientTransform="matrix(-1 0 0 1 132 -104.98)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="a72as_i6q"/><stop offset=".943" class="ptnuqol_c"/></linearGradient><path fill="url(#SVGgJ6I3bao)" class="g14r9lb1h"/><linearGradient id="SVGlZSJOdPh" x1="63.495" x2="63.495" y1="37.664" y2="99.692" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".373" class="hunkxc7oa"/><stop offset="1" class="ip0ngccya"/></linearGradient><path fill="url(#SVGlZSJOdPh)" class="egtyw04kd"/><path class="nhdov5jnt"/><linearGradient id="SVGMfdiwdou" x1="61.855" x2="61.855" y1="104.784" y2="134.021" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".202" class="sl8ua6bht"/><stop offset="1" class="ip0ngccya"/></linearGradient><path fill="url(#SVGMfdiwdou)" class="e7dxo5i8h"/><linearGradient id="SVGfl9DTdjJ" x1="49.86" x2="49.86" y1="93.309" y2="122.546" gradientTransform="matrix(0 -1 -1 0 128.026 99.695)" gradientUnits="userSpaceOnUse"><stop offset=".507" class="yakqqfb4w"/><stop offset="1" class="ip0ngccya"/></linearGradient><path fill="url(#SVGfl9DTdjJ)" class="d7adk_mex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:placard" /></template>
<style>
.a72as_i6q {
  stop-color: var(--svg-color--424242, #424242);
}

.cerf30bmr {
  d: path("m76.1 83l-20.2.02v15L76.1 98z");
}

.cld7oibet {
  fill: var(--svg-color--bf855e, #bf855e);
  d: path("M72.53 124.17H55.9V5.36c0-.75.61-1.36 1.36-1.36h13.91c.75 0 1.36.61 1.36 1.36z");
}

.d7adk_mex {
  d: path("M30.01 13.99v71.69c0 .55-.44.99-.99.99H17.43c-.55 0-.99-.44-.99-.99V13.99c0-.55.44-.99.99-.99h11.59c.54 0 .99.44.99.99");
}

.e7dxo5i8h {
  d: path("M106.31 26.56h-88.9a.97.97 0 0 1-.97-.97V13.97c0-.54.44-.97.97-.97h88.89c.54 0 .97.44.97.97v11.62c.01.54-.43.97-.96.97");
}

.egtyw04kd {
  d: path("M108.54 89.63H22.25c-.35 0-.69-.09-.99-.26l-3.97-2.23c-.52-.29-.85-.85-.85-1.45v-71.7c0-.54.44-.99.99-.99h89.1c.48 0 .96.16 1.34.45l1.89 1.45c.5.38.79.98.79 1.6v71.1c.01 1.13-.9 2.03-2.01 2.03");
}

.g14r9lb1h {
  d: path("M55.9 22.02L76.1 22V7l-20.2.02z");
}

.hunkxc7oa {
  stop-color: var(--svg-color--9e9e9e, #9e9e9e);
}

.ip0ngccya {
  stop-color: var(--svg-color--bdbdbd, #bdbdbd);
}

.lk_t5gbym {
  fill: var(--svg-color--a3673e, #a3673e);
  d: path("M76.1 124.17H59.47V4h11.96c.69 0 1.36.29 1.83.8l2.45 2.65c.25.27.39.62.39.99z");
}

.nhdov5jnt {
  fill: var(--svg-color--f5f5f5, #f5f5f5);
  d: path("M106.27 86.67H17.45c-.56 0-1.01-.45-1.01-1.01V14.01c0-.56.45-1.01 1.01-1.01h88.82c.56 0 1.01.45 1.01 1.01v71.65c0 .56-.45 1.01-1.01 1.01");
}

.ptnuqol_c {
  stop-color: var(--svg-color--424242, #424242);
  stop-opacity: 0;
}

.sl8ua6bht {
  stop-color: var(--svg-color--f5f5f5, #f5f5f5);
}

.yakqqfb4w {
  stop-color: var(--svg-color--bdbdbd, #bdbdbd);
  stop-opacity: 0;
}

</style>
