<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvynx551s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-4-outline" /></template>
<style>
.qvynx551s {
  fill: currentColor;
  d: path("M5.1 19q-.285 0-.524-.141q-.24-.142-.38-.386q-.592-1.021-.894-2.158T3 14q0-1.868.709-3.51t1.924-2.857T8.49 5.709T12 5q.383 0 .746.037q.363.036.746.104l-.652.915q-.215-.037-.42-.047T12 6Q8.65 6 6.325 8.325T4 14q0 1.05.287 2.063T5.1 18h13.794q.55-.9.825-1.925T19.994 14q0-1.616-.609-3.085q-.608-1.469-1.77-2.594l.314-1.098q1.471 1.29 2.268 3.051q.797 1.76.797 3.726q.006 1.216-.306 2.356q-.311 1.14-.89 2.194q-.14.244-.38.347q-.239.103-.524.103zm6.171-3.508q.627.292 1.256.046q.63-.246.823-.896q.667-2.194 1.284-4.378q.616-2.185 1.207-4.41q-1.325 1.879-2.611 3.744t-2.601 3.768q-.385.551-.181 1.19t.823.936m.646-1.363");
}

</style>
