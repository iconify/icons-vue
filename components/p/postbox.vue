<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="fleqh9b1n"/><path class="bpm4l8m6e"/><path class="pnhmqhbzc"/><path class="kbtu8ccxa"/><path class="r0u-07ibr"/><path class="atpi4bzmw"/><path class="z9ok_x2_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:postbox" /></template>
<style>
.atpi4bzmw {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M13 23h9.22c-1.847-2.365-6.425-8.205-7.22-9c-1-1 0-2 0-2l5-5h-9v14s0 2 2 2");
}

.bpm4l8m6e {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M31 25a4 4 0 0 1-4 4H9a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h18a4 4 0 0 1 4 4z");
}

.fleqh9b1n {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M14 28h9v8h-9z");
}

.kbtu8ccxa {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M27 12H9s-2 0-2-2V7h22v3c0 2-2 2-2 2");
}

.pnhmqhbzc {
  fill: var(--svg-color--a0041e, #a0041e);
  d: path("M7 8V6s0-2 2-2h18s2 0 2 2v2z");
}

.r0u-07ibr {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M11 7v14s0 2 2 2h10s2 0 2-2V7z");
}

.z9ok_x2_b {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M15 14c.795.795 5.373 6.635 7.22 9H23s.404-.01.848-.19L16 13l6-6h-2l-5 5s-1 1 0 2");
}

</style>
