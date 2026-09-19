<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="dx_wb_nvo"/><path class="g3u32-n-t"/><path class="cbpjbsb0t"/><circle class="uf9m42ble"/><path class="jhda52i2y"/><circle class="q8vr9p3wc"/><path class="eb8gr-bar"/><circle class="jh3q5vbne"/><path class="s8-bvpbij"/><circle class="gu7f8-jcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:tractor" /></template>
<style>
.cbpjbsb0t {
  fill: var(--svg-color--f14e3a, #f14e3a);
  d: path("M54 17c0 .7-.2 1-.9 1H28.9c-.7 0-.9-.3-.9-1v-2c0-.7.2-1 .9-1h24.2c.7 0 .9.3.9 1zM6.9 33.3L28.2 30v8.4H4.3s1.7-4.1 2.6-5.1m30.4 11.8c2-4.3 6-7.3 10.7-7.3c4.6 0 8.5 2.8 10.6 7l3.4-1.6c-2.5-5.8-7.8-9.4-14-9.4c-6.3 0-11.6 3.4-14.1 9.4z");
}

.dx_wb_nvo {
  fill: var(--svg-color--b8331e, #b8331e);
  d: path("M28.2 38.6H5.1v6.5l9.1 7.5h33.7v-14z");
}

.eb8gr-bar {
  fill: var(--svg-color--f14e3a, #f14e3a);
  d: path("M15.3 43.6c-2.3-1.1-4.8-1.5-7.1-.9c-.7-1.7-2.4-2.9-4.3-2.9V28.4H2v14.1h1.9v-.9c1.1 0 2.1.7 2.5 1.6c-.7.3-1.5.7-2.1 1.2H2v2.9h3l13.6 6.6h2.7c.2-4.5-2-8.4-6-10.3");
}

.g3u32-n-t {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M52.6 17H29.2l-2.8 21.4H5.1V40h21.1l4.4 6.4h7.1l17.8-7.8zm-4.7 19.7V24.3c-5.2 0-2.3 4.5-4.2 7.3c-2.6 3.7-7.4.4-7.4 5h-7.1l1.9-17.8h1.2v1.8c-.5.3-.8.8-.8 1.4v6.3c0 .9.8 1.7 1.7 1.7s1.7-.8 1.7-1.7V22c0-.9-.8-1.7-1.7-1.7v-1.5h17.6l1.9 17.8z");
}

.gu7f8-jcp {
  cx: 10.4px;
  cy: 53.6px;
  r: 1.9px;
  fill: var(--svg-color--3e4347, #3e4347);
}

.jh3q5vbne {
  cx: 10.4px;
  cy: 53.6px;
  r: 8.4px;
  fill: var(--svg-color--3e4347, #3e4347);
}

.jhda52i2y {
  fill: var(--svg-color--ffd45c, #ffd45c);
  d: path("M54.5 49.8c0 3.6-2.9 6.6-6.6 6.6c-3.6 0-6.6-2.9-6.6-6.6c0-3.6 2.9-6.6 6.6-6.6s6.6 3 6.6 6.6");
}

.q8vr9p3wc {
  cx: 47.9px;
  cy: 49.8px;
  r: 2.8px;
  fill: var(--svg-color--3e4347, #3e4347);
}

.s8-bvpbij {
  fill: var(--svg-color--ffd45c, #ffd45c);
  d: path("M15.1 53.6c0 2.6-2.1 4.7-4.7 4.7s-4.7-2.1-4.7-4.7s2.1-4.7 4.7-4.7s4.7 2.1 4.7 4.7");
}

.uf9m42ble {
  cx: 47.9px;
  cy: 49.8px;
  r: 12.2px;
  fill: var(--svg-color--3e4347, #3e4347);
}

</style>
