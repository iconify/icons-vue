<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="rga-cbbno"/><path class="d66ytwbfn"/><path class="h8__1bboz"/><path class="p2g1npbae"/><path class="wvh3esbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:military-medal" /></template>
<style>
.d66ytwbfn {
  fill: var(--svg-color--4b246d, #4b246d);
  d: path("M16.783 0v17.54c0 3.597 6.284 14.966 9.458 14.966h12.663c3.174 0 9.458-11.37 9.458-14.966V0z");
}

.h8__1bboz {
  fill: var(--svg-color--e88821, #e88821);
  d: path("M47.01 49.902c0 7.739-6.273 14.01-14.01 14.01s-14.01-6.274-14.01-14.01s6.276-14.01 14.01-14.01c7.738.001 14.01 6.275 14.01 14.01");
}

.p2g1npbae {
  fill: var(--svg-color--f15a29, #f15a29);
  d: path("M27.9-.035h9.919v32.592H27.9z");
}

.rga-cbbno {
  fill: var(--svg-color--f7941e, #f7941e);
  d: path("M26.18 30.01v6.493c0 1.035 1.259 1.871 2.812 1.871h8.01c1.556 0 2.814-.836 2.814-1.871V30.01H26.177");
}

.wvh3esbrj {
  fill: var(--svg-color--f2a755, #f2a755);
  d: path("M45.04 46.44q-3.92-.567-7.833-1.139c-1.164-2.354-2.323-4.708-3.487-7.06c-.167-.338-.448-.454-.728-.425c-.277-.029-.56.087-.727.425l-3.485 7.06q-3.916.572-7.833 1.139c-.643.094-.784 1.01-.371 1.408l5.604 5.464q-.654 3.807-1.305 7.614c-.125.725.542 1.317 1.237.951c2.292-1.208 4.588-2.411 6.879-3.619c2.297 1.208 4.588 2.411 6.882 3.619c.693.366 1.361-.227 1.238-.951c-.438-2.538-.87-5.076-1.308-7.614l5.605-5.464c.414-.401.276-1.314-.368-1.408");
}

</style>
