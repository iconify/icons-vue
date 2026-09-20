<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGAgNgixVn)" class="ssmu8bbej"/><path fill="url(#SVGDnPDRd0K)" class="m5mpjjb7h"/><path fill="url(#SVGCtsVKefD)" class="a-gh-rtge"/><defs><linearGradient id="SVGAgNgixVn" x1="3.001" x2="21.431" y1="16.322" y2="15.591" gradientUnits="userSpaceOnUse"><stop class="xnhgfvelh"/><stop offset="1" class="e95k-_nlt"/></linearGradient><linearGradient id="SVGDnPDRd0K" x1="3.001" x2="21.323" y1="16.973" y2="16.366" gradientUnits="userSpaceOnUse"><stop class="vn425acga"/><stop offset="1" class="aedq3aciz"/></linearGradient><linearGradient id="SVGCtsVKefD" x1="4.035" x2="20.302" y1="12.002" y2="12.002" gradientUnits="userSpaceOnUse"><stop class="qgid28b8y"/><stop offset="1" class="vuhk_l2ol"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sol" /></template>
<style>
.a-gh-rtge {
  d: path("M18.413 10.472a.6.6 0 0 0-.411-.158H3.58c-.512 0-.77.58-.416.922l2.368 2.29a.62.62 0 0 0 .41.163h14.479c.517 0 .77-.585.41-.928z");
}

.aedq3aciz {
  stop-color: var(--svg-color--73b0d0, #73b0d0);
}

.e95k-_nlt {
  stop-color: var(--svg-color--47f8c3, #47f8c3);
}

.ft5dv1b6b {
  fill: none;
}

.m5mpjjb7h {
  d: path("M18.413 19.157a.6.6 0 0 1-.411.157H3.58c-.512 0-.77-.58-.416-.923l2.368-2.289a.6.6 0 0 1 .41-.163h14.479c.517 0 .77.585.41.928z");
}

.qgid28b8y {
  stop-color: var(--svg-color--778cbf, #778cbf);
}

.ssmu8bbej {
  d: path("M18.413 7.903a.62.62 0 0 1-.411.164H3.58c-.512 0-.77-.585-.416-.929l2.368-2.283a.6.6 0 0 1 .41-.169h14.479c.517 0 .77.59.41.934z");
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

</style>
