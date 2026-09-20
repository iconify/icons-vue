<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="zjy9f2b5h"/><path class="n3bvbu08r"/><path class="xqc3vxkxa"/><path class="bqtc_37su"/><path class="j8e3u0bst"/><path class="z8knugbvr"/><path class="p-p58wsxq"/><path class="gntkwhuoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:toolbox" /></template>
<style>
.bqtc_37su {
  fill: var(--svg-color--be1931, #be1931);
  d: path("M0 15h36v2H0zm4 9h28v2H4zm0 6h28v2H4z");
}

.gntkwhuoa {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M26 15h2v3h-2zM8 15h2v3H8z");
}

.j8e3u0bst {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M4 28h28v2H4z");
}

.n3bvbu08r {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M36 31.765S36 36 31.765 36H4.235C0 36 0 31.765 0 31.765V11.647c0-4.235 4.235-4.235 4.235-4.235h27.529s4.235 0 4.235 4.235z");
}

.p-p58wsxq {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M25 17v1a1 1 0 0 0 1 1h2a1 1 0 0 0 1-1v-1zM7 17v1a1 1 0 0 0 1 1h2a1 1 0 0 0 1-1v-1z");
}

.xqc3vxkxa {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M4 22h28v2H4z");
}

.z8knugbvr {
  fill: var(--svg-color--aab8c2, #aab8c2);
  d: path("M10 19H8a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1m18 0h-2a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1");
}

.zjy9f2b5h {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M26 .5H10C8.07.5 6.5 2.07 6.5 4v4h3V4c0-.271.229-.5.5-.5h16c.271 0 .5.229.5.5v4h3V4c0-1.93-1.57-3.5-3.5-3.5");
}

</style>
