<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kwuuvwbzr"/><path class="nfeujor-m"/><path class="novumccsd"/><path class="x152bzbjv"/><path class="zmnhakbwg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:naka" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kwuuvwbzr {
  fill: var(--svg-color--fff, #fff);
  d: path("M21 3H3v18h18z");
}

.nfeujor-m {
  fill: var(--svg-color--c10606, #c10606);
  d: path("M3 3h18v18H3z");
}

.novumccsd {
  fill: var(--svg-color--7f0404, #7f0404);
  d: path("M15.317 12.585c-.225 1.029-1.199.862-1.199.862c-1.054-.129-.957-1.447-.957-1.447h2.153v.585zm-4.995.862s-.99.225-1.215-.804V12h2.173s.097 1.318-.958 1.447m-1.257-3.205s-.475.02-.475-.415v-.475H7.452v1.555H6.054V12h1.382v.508H6.054v1.1l1.552-.01s.434 1.938 2.485 1.938c.09 0 1.427 0 2.131-1.254c.582 1.254 2.028 1.254 2.125 1.254c2.054 0 2.494-1.929 2.494-1.929h1.588v-1.099h-1.424V12h1.424v-1.093h-1.44V9.352H15.85v.475c0 .434-.476.415-.476.415z");
}

.x152bzbjv {
  fill: var(--svg-color--ccc, #ccc);
  d: path("M15.054 12.193c-.225 1.028-1.2.861-1.2.861c-1.05-.128-.89-.893-.89-1.376h2.09zm-4.992.861s-.99.167-1.215-.861v-.514h2.173s.096 1.243-.958 1.375M8.802 9.85s-.473.019-.473-.412v-.482H7.191v1.559h-1.44v1.163H7.18v.438H5.768v1.17h1.578s.43 1.928 2.484 1.928c0 0 1.479.129 2.128-1.253c.653 1.382 2.131 1.253 2.131 1.253c2.051 0 2.482-1.928 2.482-1.928h1.578v-1.17H16.82v-.437h1.347v-1.164h-1.443V8.959h-1.138v.48c0 .43-.476.41-.476.41z");
}

.zmnhakbwg {
  fill: var(--svg-color--f2f2f2, #f2f2f2);
  d: path("M14.893 11.929c-.225 1.031-1.167.864-1.167.864c-1.054-.131-.958-1.436-.958-1.436h2.125zm-4.963.864s-.92.168-1.144-.864v-.572h2.102s.096 1.305-.958 1.436M8.618 9.75s-.475.02-.475-.411v-.553h-.965v1.607H5.571v.965h1.607V12H5.571v.964h1.662s.415 1.928 2.465 1.928c0 0 1.479.129 2.131-1.253c.65 1.382 2.128 1.253 2.128 1.253c2.054 0 2.37-1.928 2.37-1.928h1.71v-.965H16.5v-.642h1.536v-.965H16.5V8.785h-.964v.553c0 .43-.476.411-.476.411z");
}

</style>
