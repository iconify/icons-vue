<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="r0eyauc9s"/><path class="khpxl2_nf"/><path class="wlini3bdf"/><path class="b1bmu5b1u"/><g class="lqb-76dif"><path class="p6_upn-3o"/><path class="e7pj5bbzg"/></g><path class="hr_y87bas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:ribbon" /></template>
<style>
.b1bmu5b1u {
  fill: var(--svg-color--ff5760, #ff5760);
  d: path("M33.3 14c0 5.1 5.7 10 12.6 11l5.5.8c6.9 1 11.6-1.3 10.4-5s-1.2-9.8 0-13.5s-3.4-6-10.4-5l-5.5.7c-6.9.9-12.6 5.9-12.6 11");
}

.e7pj5bbzg {
  d: path("M32 20.9c-3.7 0-4.7 2.8-4.7-6.8s.9-6.8 4.7-6.8s4.7-2.8 4.7 6.8s-1 6.8-4.7 6.8");
}

.hr_y87bas {
  fill: var(--svg-color--ff5760, #ff5760);
  d: path("M32 21.1c-3 0-3.8 2.8-3.8-7c0-9.9.7-7 3.8-7s3.8-2.8 3.8 7s-.8 7-3.8 7");
}

.khpxl2_nf {
  fill: var(--svg-color--ff5760, #ff5760);
  d: path("M30.7 14c0 5.1-5.7 10-12.6 11l-5.5.8c-6.9 1-11.6-1.3-10.4-5s1.2-9.8 0-13.5s3.4-6 10.4-5l5.5.7c6.9.9 12.6 5.9 12.6 11");
}

.lqb-76dif {
  fill: var(--svg-color--c94747, #c94747);
}

.p6_upn-3o {
  d: path("M60.1 21.3c.5.5-.1 1.1-.3 1.3c-.6.7-2.3 1.5-5.3 1.5c-.9 0-1.8-.1-2.8-.2l-5.5-.8c-3.9-.5-7.4-2.5-9.3-5c0 .1 16.8-3 23.2 3.2m-28.9-8.8s-1.7 1.4-5.8-2c-4.7-3.9-11.5 1.3-2.4 3.6c4.9 1.3 8.2-1.6 8.2-1.6m1.6 0s1.7 1.4 5.8-2c4.7-3.9 11.5 1.3 2.4 3.6c-4.9 1.3-8.2-1.6-8.2-1.6");
}

.r0eyauc9s {
  fill: var(--svg-color--c94747, #c94747);
  d: path("M15.3 13.1S16 33.3 2 46h13v16s13.6-19.2 13.6-48.9zm33.4 0S48 33.3 62 46H49v16S35.4 42.8 35.4 13.1z");
}

.wlini3bdf {
  fill: var(--svg-color--c94747, #c94747);
  d: path("M3.9 21.3c-.5.5.1 1.1.3 1.3c.6.7 2.3 1.5 5.3 1.5c.9 0 1.8-.1 2.8-.2l5.5-.8c3.9-.5 7.4-2.5 9.3-5c0 .1-16.8-3-23.2 3.2");
}

</style>
