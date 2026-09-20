<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="vv2bgzb6f"/><path class="t_4i_7b4z"/><path class="uqst1-_ls"/><path class="rt5_g8bsq"/><path class="sijk98bmc"/><path class="ttocz-8lc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:sailboat" /></template>
<style>
.rt5_g8bsq {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M5 22s2-5 5-9s8-8 8-8s-1 11-1 16v1s-3-1-6-1s-6 1-6 1");
}

.sijk98bmc {
  fill: var(--svg-color--f4900c, #f4900c);
  d: path("M20 2s6 6 9 11c2.771 4.618 4 9 4 9s-3-1-6-1s-6 1-6 1v-1c0-9-1-19-1-19");
}

.t_4i_7b4z {
  fill: var(--svg-color--d1d3d4, #d1d3d4);
  d: path("M3 24h31v8H12c-6 0-9-8-9-8");
}

.ttocz-8lc {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M2 24a1 1 0 1 0 0 2h33v-2z");
}

.uqst1-_ls {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M0 30h36v6H0z");
}

.vv2bgzb6f {
  fill: var(--svg-color--a7a9ac, #a7a9ac);
  d: path("M20 26a1 1 0 1 1-2 0V1a1 1 0 0 1 2 0z");
}

</style>
