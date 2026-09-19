<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="yedt8gsom"/><path class="k-2eb9b0m"/><path class="hd6fmj95m"/><circle class="qlzdbl1rg"/><circle class="xb4gxb90b"/><circle class="l4nx1_cak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:vertical-traffic-light" /></template>
<style>
.hd6fmj95m {
  fill: var(--svg-color--152228, #152228);
  d: path("M26.849 48.714V15.246c0-5.631 3.706-10.395 8.806-11.993a12.6 12.6 0 0 0-3.758-.572c-6.938 0-12.564 5.626-12.564 12.564v33.468c0 6.94 5.626 12.564 12.564 12.564c1.309 0 2.572-.2 3.758-.573c-5.1-1.595-8.806-6.361-8.806-11.99");
}

.k-2eb9b0m {
  fill: var(--svg-color--1f2e35, #1f2e35);
  d: path("M44.46 48.716c0 6.938-5.624 12.562-12.564 12.562c-6.938 0-12.564-5.624-12.564-12.562v-33.47c0-6.938 5.626-12.564 12.564-12.564c6.94 0 12.564 5.626 12.564 12.564z");
}

.l4nx1_cak {
  cx: 31.897px;
  cy: 50.26px;
  r: 8.121px;
  fill: var(--svg-color--4fba80, #4fba80);
}

.qlzdbl1rg {
  cx: 31.897px;
  cy: 13.656px;
  r: 8.121px;
  fill: var(--svg-color--ec1c24, #ec1c24);
}

.xb4gxb90b {
  cx: 31.897px;
  cy: 31.979px;
  r: 8.121px;
  fill: var(--svg-color--ffdd15, #ffdd15);
}

.yedt8gsom {
  fill: var(--svg-color--bfc7cb, #bfc7cb);
  d: path("M46.594 50.28c0 7.577-6.625 13.723-14.797 13.723c-8.171 0-14.796-6.146-14.796-13.723V13.724c0-7.577 6.625-13.721 14.795-13.721c8.172 0 14.797 6.144 14.797 13.721z");
}

</style>
