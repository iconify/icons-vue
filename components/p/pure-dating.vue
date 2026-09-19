<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m4u5-wgmq"/><path class="w095ixbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pure-dating" /></template>
<style>
.m4u5-wgmq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.084 42.5c-2.186-3.213-10.027-2.649-9.604-8.797c2.885-1.16 4.792-4.26 4.792-8.617c0-5.588-3.316-9.808-7.636-9.808S17 19.808 17 25.397c0 3.392 1.294 5.907 3.275 7.365c1.316 7.153-7.19 6.37-9.483 9.738");
}

.w095ixbcx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.822 22.324c-1.851 0-3.44.998-4.118 2.42c.678 1.424 2.267 2.422 4.118 2.422s3.44-.998 4.118-2.421c-.679-1.423-2.267-2.421-4.118-2.421m0 3.352v-1.862m-7.796.738C4.806 20.386 6.927 11.646 9.317 5.5c.497 4.904 3.11 14.17 9.718 12.967M32.272 24.1c9.63-4.073 9.197-12.454 6.807-18.6c-.335 5.47-4.208 13.06-8.336 13.573");
}

</style>
