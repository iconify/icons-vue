<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="r-vb__b3c"/><path class="ju9cp0nms"/><path class="wz_9c3bor"/><path class="esx49yb-o"/><path class="tahcwkb8z"/><path class="m14ilsd6r"/><path class="p0aa3vbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:shamrock" /></template>
<style>
.esx49yb-o {
  fill: var(--svg-color--7bb246, #7bb246);
  d: path("M57.8 22c-9.7-6.5-24.2 7.3-25.8 9.3l22.3 6.1c5.6 0 12.2-9.6 3.5-15.4M16.2 8.2c-3.7 11.3 14.5 21.4 15.8 23V7.6c-1.4-5.4-12.4-9.5-15.8.6");
}

.ju9cp0nms {
  fill: var(--svg-color--699635, #699635);
  d: path("M31.1 62h-7s6.3-15.6 6.3-32.1c0-.8 3.2-.8 3.2 0c0 17.2-2.5 32.1-2.5 32.1");
}

.m14ilsd6r {
  fill: var(--svg-color--7bb246, #7bb246);
  d: path("M9.7 37.4c-4.6 2.3-6.1 14.5 4.5 15.1c11.4.7 16.9-19.6 17.8-21.2z");
}

.p0aa3vbsy {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M6.2 22c-8.7 5.9-2.1 15.4 3.5 15.4L32 31.3c-1.7-2-16.1-15.8-25.8-9.3");
}

.r-vb__b3c {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M57.8 22c-4.9-3.3-11-1.4-16.1 1.5c4.3-4.2 8-9.7 6.1-15.3C44.3-2.1 33 2.5 32 7.7c-1.4-5.5-12.4-9.6-15.8.5c-1.9 5.8 2 11.3 6.3 15.5c-5.1-3-11.4-5.1-16.3-1.8c-8.7 5.9-2.1 15.4 3.5 15.4c-4.6 2.3-6.1 14.5 4.5 15.1c8.2.5 13.4-9.9 15.9-16.3l3.4-.9C36 41.6 41.2 53 49.8 52.5c10.6-.7 9.1-12.8 4.5-15.1c5.6 0 12.2-9.6 3.5-15.4");
}

.tahcwkb8z {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M47.8 8.2C44.3-2.1 33 2.5 32 7.7v23.6c1.3-1.4 19.5-11.9 15.8-23.1");
}

.wz_9c3bor {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M49.8 52.5c10.6-.7 9.1-12.8 4.5-15.1L32 31.3c.9 1.6 6.4 21.9 17.8 21.2");
}

</style>
