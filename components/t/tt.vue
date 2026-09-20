<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGmFCxIDFC)" class="fkjenubdo"/><defs><linearGradient id="SVGmFCxIDFC" x1="11.995" x2="11.995" y1="3.532" y2="20.468" gradientUnits="userSpaceOnUse"><stop class="zwdf8tbhz"/><stop offset="1" class="tr4subcwo"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tt" /></template>
<style>
.fkjenubdo {
  d: path("m7.215 19.622l4.626-7.33c.07-.112-.01-.292-.143-.292H7.65c-.328 0-.529-.323-.354-.603l4.98-8.39l-.28-.005a8.998 8.998 0 0 0-4.78 16.62m4.515 1.376h.265a8.998 8.998 0 0 0 4.79-16.62l-4.441 7.363a.17.17 0 0 0 .143.26h4.35c.329 0 .572.401.398.682l-5.51 8.31z");
}

.ft5dv1b6b {
  fill: none;
}

.tr4subcwo {
  stop-color: var(--svg-color--0502da, #0502da);
}

.zwdf8tbhz {
  stop-color: var(--svg-color--06fcd7, #06fcd7);
}

</style>
