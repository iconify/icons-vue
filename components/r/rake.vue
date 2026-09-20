<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bod829tgu"/><path class="d9-f1bp4r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rake" /></template>
<style>
.bod829tgu {
  fill: var(--svg-color--12cf9c, #12cf9c);
  d: path("m7.579 4.159l2.734 10.935L21 11.966V12A9 9 0 1 1 7.579 4.159");
}

.d9-f1bp4r {
  fill: var(--svg-color--133932, #133932);
  d: path("m9.976 3.226l2.306 8.213l8.302-2.143a9 9 0 0 0-.94-2.042L13.97 8.907l-1.535-5.895a9 9 0 0 0-2.458.22z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
