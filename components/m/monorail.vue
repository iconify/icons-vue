<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="kizai5juq"/><path class="r7how8xwl"/><path class="eldcobchn"/><path class="z1unpjbpo"/><path class="uacmwszyb"/><path class="dwzqzs-dn"/><path class="hcnadr6cx"/><path class="wh2bpqb-n"/><path class="kyj5ulb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:monorail" /></template>
<style>
.dwzqzs-dn {
  fill: var(--svg-color--bcbec0, #bcbec0);
  d: path("M11 20s.751.938 1.844 2H36v-2z");
}

.eldcobchn {
  fill: var(--svg-color--6d6e71, #6d6e71);
  d: path("M6 27h4v3H6zm10 0h4v3h-4zm10 0h4v3h-4z");
}

.hcnadr6cx {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M36 20H10c-3 0-7-3-7-6C3 9 19 2 21 2h15z");
}

.kizai5juq {
  fill: var(--svg-color--6d6e71, #6d6e71);
  d: path("M0 24h36v4H0z");
}

.kyj5ulb8c {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M21 4h-5.553c-3.327 1.524-7.344 3.738-9.898 6H21a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2m5 5a1 1 0 1 1-2 0V5a1 1 0 1 1 2 0zm8 0a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1z");
}

.r7how8xwl {
  fill: var(--svg-color--939598, #939598);
  d: path("M0 22h36v4H0zm6 6h4v8H6zm10 0h4v8h-4zm10 0h4v8h-4z");
}

.uacmwszyb {
  fill: var(--svg-color--d1d3d4, #d1d3d4);
  d: path("M36 20v5H18c-3 0-7-5-7-5z");
}

.wh2bpqb-n {
  fill: var(--svg-color--5c913b, #5c913b);
  d: path("M3.741 12C3.28 12.686 3 13.36 3 14c0 1.655 1.22 3.308 2.816 4.459C21.231 14 36 14 36 14v-2z");
}

.z1unpjbpo {
  fill: var(--svg-color--bcbec0, #bcbec0);
  d: path("M36 0h-6a2 2 0 0 0-2 2v2a2 2 0 0 0 2 2h6z");
}

</style>
