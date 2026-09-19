<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><path class="d28svts1u"/><path class="y_ovl8bye"/><path class="e7j7ups7y"/><path class="o3e-eq19y"/><path class="kke43vd-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:sleepy-face" /></template>
<style>
.d28svts1u {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M43.8 48.3c0 6.3-5.3 8.4-11.8 8.4s-11.8-2.1-11.8-8.4c0-8.3 5.3-13.7 11.8-13.7S43.8 40 43.8 48.3");
}

.e7j7ups7y {
  fill: var(--svg-color--ff717f, #ff717f);
  d: path("M32 50.7c-6.4 0-8.3 2-8.3 2c1.6 2.8 8.3 2.6 8.3 2.6s6.6.2 8.3-2.6c0 0-1.9-2-8.3-2");
}

.kke43vd-c {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M35.9 20.5c4.2 8 12.7 8 16.9 0c.2-.4-.3-.6-1-1c-4.2 3.3-11.1 3-14.9 0c-.6.5-1.2.6-1 1m-24.7 0c4.2 8 12.7 8 16.9 0c.2-.4-.3-.6-1-1c-4.2 3.3-11.1 3-14.9 0c-.7.5-1.2.6-1 1");
}

.o3e-eq19y {
  fill: var(--svg-color--52e8b6, #52e8b6);
  d: path("M30.1 26.8c-1.3-.7-4.1 7.9-8.5 8.7c-.4-.5-.9-1-1.4-1.4c-4.2-3.5-10.7-2.8-14.5 1.8c-3.8 4.5-3.4 11.1.8 14.6c4.2 3.6 10.7 2.8 14.5-1.8c4.9-5.8 10.8-21 9.1-21.9");
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.y_ovl8bye {
  fill: var(--svg-color--4c3526, #4c3526);
  d: path("M34.7 39c-.8 0-2.1.8-1.7 2.9c.2 1.1 1.7 2.4 1.7 4.1c0 3.5-5.5 3.5-5.5 0c0-1.7 1.5-3 1.7-4.1c.5-2.1-.8-2.9-1.7-2.9c-2.3.1-6.1 2.6-6.1 6.8c0 4.8 3.9 8.7 8.8 8.7s8.8-3.9 8.8-8.7c.1-4.2-3.7-6.8-6-6.8");
}

</style>
