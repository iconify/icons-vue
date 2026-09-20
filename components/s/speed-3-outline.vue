<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxfjt-3nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-3-outline" /></template>
<style>
.qxfjt-3nd {
  fill: currentColor;
  d: path("M5.106 19q-.285 0-.524-.103t-.38-.347q-.579-1.054-.89-2.194T3.006 14q0-1.966.797-3.726t2.268-3.051l.314 1.098q-1.162 1.125-1.77 2.594q-.61 1.469-.61 3.085q0 1.05.276 2.075T5.107 18h13.792q.525-.925.813-1.937T20 14q0-3.35-2.325-5.675T12 6q-.215 0-.42.01t-.42.046l-.652-.916q.383-.067.746-.104T12 5q1.868 0 3.51.709t2.858 1.924t1.923 2.857T21 14q0 1.177-.302 2.315t-.894 2.158q-.14.244-.38.386q-.24.141-.524.141zm7.623-3.508q.619-.298.823-.936t-.18-1.19q-1.316-1.903-2.602-3.768T8.16 5.854q.59 2.225 1.206 4.41q.617 2.184 1.284 4.378q.194.65.823.896t1.256-.046m-.646-1.363");
}

</style>
