<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ho_d0n5jn"/><path class="g51zifb9i"/><path class="cpn5_6ena"/><g class="pclzssrrw"><path class="hca_7ubud"/><path class="m36e6qb5l"/><path class="wo38kgb2m"/></g><path class="xub40db3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:pen" /></template>
<style>
.cpn5_6ena {
  fill: var(--svg-color--59595c, #59595c);
  d: path("m9.409 50.685l9.808 7.815l35.681-40.166L40.56 6.917z");
}

.g51zifb9i {
  fill: var(--svg-color--a7a8ac, #a7a8ac);
  d: path("M16.834 55.701c1.089 1.093 1.517 2.129.447 3.472c-1.607 2.02-8.01 6.161-10.349 4.299c-.354-.283-.583-.7-.731-1.187c4.28-1.2 9.48-2.942 10.633-6.584");
}

.hca_7ubud {
  d: path("m16.195 56.09l3.02 2.41l35.681-40.17l-5.28-4.204zm-3.771-3l-3.01-2.405l31.15-43.768l5.286 4.211z");
}

.ho_d0n5jn {
  fill: var(--svg-color--bcbdbf, #bcbdbf);
  d: path("M8.807 52.42c1.607-2.01 3.654-.324 5.996 1.545c2.34 1.863 4.085 3.192 2.479 5.208c-1.607 2.02-8.01 6.161-10.349 4.299c-2.339-1.866.263-9.03 1.874-11.05");
}

.m36e6qb5l {
  d: path("M40.706 4.875c-1.639 2.053-1.237 5.106.897 6.803l8.418 6.708c2.135 1.697 5.198 1.407 6.842-.649c1.637-2.057 1.231-5.106-.901-6.803l-8.424-6.708c-2.133-1.703-5.192-1.414-6.832.649");
}

.pclzssrrw {
  fill: var(--svg-color--424143, #424143);
}

.wo38kgb2m {
  d: path("M47.13 13.384c2.318 1.844 5.21 2.076 6.455.516l4.913-6.171c1.245-1.566.373-4.328-1.943-6.177c-2.314-1.85-5.212-2.076-6.457-.512l-4.913 6.17c-1.244 1.561-.375 4.325 1.945 6.174");
}

.xub40db3r {
  fill: var(--svg-color--bcbdbf, #bcbdbf);
  d: path("M33.99 33.29c1.117 1 2.821.903 3.824-.213L51.682 17.59a2.7 2.7 0 0 0-.203-3.824a2.71 2.71 0 0 0-3.824.217l-13.87 15.485c-1 1.113-.91 2.824.205 3.822");
}

</style>
