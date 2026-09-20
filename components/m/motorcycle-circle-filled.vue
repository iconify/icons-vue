<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGTgST5crt"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path class="a-l37qlir"/><path clip-rule="evenodd" class="tm3007bhz"/><path class="n9mys9bqg"/><path clip-rule="evenodd" class="gxq-ctbxd"/><path class="r2i5iwbba"/><path class="c74qz6uav"/></g></mask></defs><circle mask="url(#SVGTgST5crt)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:motorcycle-circle-filled" /></template>
<style>
.a-l37qlir {
  d: path("M15.75 15.5a1 1 0 1 1-2 0a1 1 0 0 1 2 0m-3.5 0a1 1 0 1 1-2 0a1 1 0 0 1 2 0");
}

.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.c74qz6uav {
  d: path("m6.41 7.046l.476-1.455l4.524.863l-.477 1.456zm8.18-.592l.477 1.456l4.523-.864l-.476-1.455z");
}

.ft5dv1b6b {
  fill: none;
}

.gxq-ctbxd {
  fill-rule: evenodd;
  d: path("M18 14a5 5 0 0 0-10 0v2.5a2.5 2.5 0 0 0 2.5 2.5h5a2.5 2.5 0 0 0 2.5-2.5zm-8 0a3 3 0 0 1 6 0v2.5a.5.5 0 0 1-.5.5h-5a.5.5 0 0 1-.5-.5z");
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.n9mys9bqg {
  d: path("M13 17a2 2 0 0 1 2 2v1.5a2 2 0 1 1-4 0V19a2 2 0 0 1 2-2");
}

.r2i5iwbba {
  d: path("M18.5 7.5a1 1 0 1 1 0-2h2a1 1 0 1 1 0 2zm-13 0a1 1 0 0 1 0-2h2a1 1 0 0 1 0 2z");
}

.tm3007bhz {
  fill-rule: evenodd;
  d: path("M13 11a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7m0-5a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3");
}

</style>
