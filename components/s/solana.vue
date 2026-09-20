<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGzrxqqeia)" class="npbeq7blj"/><path fill="url(#SVGjVQeOkmE)" class="qhogdiqve"/><path fill="url(#SVGRPwOObRg)" class="xu2l3ybok"/><defs><linearGradient id="SVGzrxqqeia" x1="3.001" x2="21.459" y1="55.041" y2="54.871" gradientUnits="userSpaceOnUse"><stop class="xnhgfvelh"/><stop offset="1" class="e95k-_nlt"/></linearGradient><linearGradient id="SVGjVQeOkmE" x1="3.001" x2="21.341" y1="9.168" y2="9.027" gradientUnits="userSpaceOnUse"><stop class="vn425acga"/><stop offset="1" class="aedq3aciz"/></linearGradient><linearGradient id="SVGRPwOObRg" x1="4.036" x2="20.303" y1="12.003" y2="12.003" gradientUnits="userSpaceOnUse"><stop class="qgid28b8y"/><stop offset="1" class="vuhk_l2ol"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:solana" /></template>
<style>
.aedq3aciz {
  stop-color: var(--svg-color--73b0d0, #73b0d0);
}

.e95k-_nlt {
  stop-color: var(--svg-color--47f8c3, #47f8c3);
}

.ft5dv1b6b {
  fill: none;
}

.npbeq7blj {
  d: path("M18.413 7.902a.62.62 0 0 1-.411.163H3.58c-.512 0-.77-.585-.416-.928l2.369-2.284a.6.6 0 0 1 .41-.169H20.42c.517 0 .77.59.41.935z");
}

.qgid28b8y {
  stop-color: var(--svg-color--778cbf, #778cbf);
}

.qhogdiqve {
  d: path("M18.413 19.158a.62.62 0 0 1-.411.158H3.58c-.512 0-.77-.58-.416-.923l2.369-2.29a.6.6 0 0 1 .41-.163H20.42c.517 0 .77.586.41.928z");
}

.vn425acga {
  stop-color: var(--svg-color--c44fe2, #c44fe2);
}

.vuhk_l2ol {
  stop-color: var(--svg-color--5dcdc9, #5dcdc9);
}

.xnhgfvelh {
  stop-color: var(--svg-color--599db0, #599db0);
}

.xu2l3ybok {
  d: path("M18.413 10.473a.62.62 0 0 0-.411-.158H3.58c-.512 0-.77.58-.416.923l2.369 2.29c.111.103.257.16.41.163H20.42c.517 0 .77-.586.41-.928z");
}

</style>
