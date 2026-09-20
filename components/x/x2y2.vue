<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGPyJd5bLe)" class="p_pr36bee"/><path fill="url(#SVGEz9yMdMt)" class="d8vu6gbna"/><path fill="url(#SVGmhzTAbTu)" clip-rule="evenodd" class="apzzvjmde"/><defs><linearGradient id="SVGPyJd5bLe" x1="3.003" x2="22.727" y1="12.565" y2="12.565" gradientUnits="userSpaceOnUse"><stop class="lwjj23boh"/><stop offset="1" class="xj5vtbt4h"/></linearGradient><linearGradient id="SVGEz9yMdMt" x1="-6.574" x2="21" y1="12.749" y2="12.749" gradientUnits="userSpaceOnUse"><stop class="lwjj23boh"/><stop offset="1" class="xj5vtbt4h"/></linearGradient><linearGradient id="SVGmhzTAbTu" x1="3.003" x2="21.001" y1="12.565" y2="12.565" gradientUnits="userSpaceOnUse"><stop class="lwjj23boh"/><stop offset="1" class="xj5vtbt4h"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:x2y2" /></template>
<style>
.apzzvjmde {
  fill-rule: evenodd;
  d: path("M12.283 17.627a5.343 5.343 0 1 0 0-10.686a5.343 5.343 0 0 0 0 10.686m0-1.687a3.656 3.656 0 1 0 0-7.312a3.656 3.656 0 0 0 0 7.312");
}

.d8vu6gbna {
  d: path("M13.97 18.752c3.88 0 7.03-3.02 7.03-6.75s-3.15-6.75-7.03-6.75c-1.817 0-3.47.665-4.72 1.744c.861-.45 1.846-.618 2.892-.618c3.374 0 6.046 2.328 6.046 5.624s-2.666 6.232-6.046 6.232q-.574 0-1.114-.101c.894.393 1.89.619 2.942.619");
}

.ft5dv1b6b {
  fill: none;
}

.lwjj23boh {
  stop-color: var(--svg-color--02dffc, #02dffc);
}

.p_pr36bee {
  d: path("M19.426 6.924a7.72 7.72 0 0 0-5.456-2.233c-4.196 0-7.593 3.273-7.593 7.312s3.397 7.311 7.593 7.311a7.7 7.7 0 0 0 5.456-2.232A8.998 8.998 0 0 1 3 12a8.999 8.999 0 0 1 16.426-5.082z");
}

.xj5vtbt4h {
  stop-color: var(--svg-color--5831c9, #5831c9);
}

</style>
