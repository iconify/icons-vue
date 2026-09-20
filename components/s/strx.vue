<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGA2k08bQR)" class="iffx5mbty"/><defs><linearGradient id="SVGA2k08bQR" x1="5.596" x2="18.366" y1="5.218" y2="17.613" gradientUnits="userSpaceOnUse"><stop class="os8ml0b3o"/><stop offset=".69" class="i9_u8pv0w"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:strx" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i9_u8pv0w {
  stop-color: var(--svg-color--4950d4, #4950d4);
}

.iffx5mbty {
  d: path("M12.021 9.67L4.128 3l13.314 2.541zM10.443 21L3.53 3.688l8.153 6.724zm8.873-15.247l-6.31 5.188h4.95l-6.618 9.8l9.133-10.859h-4.395z");
}

.os8ml0b3o {
  stop-color: var(--svg-color--73d8e2, #73d8e2);
}

</style>
