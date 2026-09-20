<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bz7p86qhc"/><path class="olm368m6h"/><path class="dcmyjxbgv"/><path class="fw4xfgb0j"/><path class="hxmq333-e"/><path class="wo3fj5ehc"/><path class="r1oulwkyw"/><path class="kxt01ipcd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:versa" /></template>
<style>
.bz7p86qhc {
  fill: var(--svg-color--2b2d78, #2b2d78);
  d: path("M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

.dcmyjxbgv {
  fill: var(--svg-color--5c5d96, #5c5d96);
  d: path("M12 18.274a6.274 6.274 0 1 0 0-12.547a6.274 6.274 0 0 0 0 12.547");
}

.ft5dv1b6b {
  fill: none;
}

.fw4xfgb0j {
  fill: var(--svg-color--7373a5, #7373a5);
  d: path("M12 16.833a4.833 4.833 0 1 0 0-9.667a4.833 4.833 0 0 0 0 9.667");
}

.hxmq333-e {
  fill: var(--svg-color--898bb4, #898bb4);
  d: path("M12 15.44a3.441 3.441 0 1 0 0-6.881a3.441 3.441 0 0 0 0 6.882");
}

.kxt01ipcd {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.006 17.294L7.305 7.235h1.927l2.774 5.962l2.859-5.962h1.842z");
}

.olm368m6h {
  fill: var(--svg-color--434487, #434487);
  d: path("M12 19.687a7.687 7.687 0 1 0 0-15.374a7.687 7.687 0 0 0 0 15.374");
}

.r1oulwkyw {
  fill: var(--svg-color--b1b1cd, #b1b1cd);
  d: path("M12 13.027a1.027 1.027 0 1 0 0-2.054a1.027 1.027 0 0 0 0 2.054");
}

.wo3fj5ehc {
  fill: var(--svg-color--9f9fc1, #9f9fc1);
  d: path("M12 14.192a2.192 2.192 0 1 0 0-4.383a2.192 2.192 0 0 0 0 4.383");
}

</style>
