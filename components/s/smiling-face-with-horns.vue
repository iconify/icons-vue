<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="ni6ivac4z"/><path class="o82qwns7l"/><path class="xrle-unhp"/><path class="dn_rboe7h"/><g class="vxz8xgbto"><path class="dvcbqu9cs"/><path class="kld6apb1i"/></g><path class="b5_bk0xsq"/><g class="vxz8xgbto"><path class="o7elgg71u"/><path class="m6h5wyq9p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:smiling-face-with-horns" /></template>
<style>
.b5_bk0xsq {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.7 26.8c-2 4.3-.1 9.4 4.2 11.4s9.4.1 11.4-4.2c1.5-3.2-14.1-10.5-15.6-7.2");
}

.dn_rboe7h {
  fill: var(--svg-color--fff, #fff);
  d: path("M52.3 26.8c2 4.3.1 9.4-4.2 11.4s-9.4.1-11.4-4.2c-1.5-3.2 14.1-10.5 15.6-7.2");
}

.dvcbqu9cs {
  d: path("M49.8 27.9c1.4 2.9.1 6.4-2.8 7.7c-2.9 1.4-6.4.1-7.7-2.8c-1-1.8 9.6-6.7 10.5-4.9");
}

.kld6apb1i {
  d: path("M53.9 27.1c-1.9.2-3.5.5-5.2.9c-1.6.4-3.1 1-4.6 1.7q-2.25 1.05-4.2 2.4c-1.4 1-2.6 2.1-4 3.4c.2-1.9 1.1-3.7 2.4-5.1c1.2-1.5 2.9-2.6 4.6-3.4c1.8-.8 3.7-1.3 5.6-1.3c1.9-.1 3.8.4 5.4 1.4");
}

.m6h5wyq9p {
  d: path("M10.1 27.1c1.6-1 3.5-1.5 5.4-1.4c1.9 0 3.8.5 5.6 1.3c1.7.8 3.3 2 4.6 3.4c1.2 1.5 2.2 3.2 2.4 5.1c-1.3-1.3-2.6-2.4-4-3.4s-2.8-1.8-4.2-2.4c-1.5-.7-3-1.2-4.6-1.7c-1.7-.5-3.3-.7-5.2-.9");
}

.ni6ivac4z {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--f46767, #f46767);
}

.o7elgg71u {
  d: path("M14.2 27.9c-1.4 2.9-.1 6.4 2.8 7.7c2.9 1.4 6.4.1 7.7-2.8c1-1.8-9.6-6.7-10.5-4.9");
}

.o82qwns7l {
  fill: var(--svg-color--ffdd67, #ffdd67);
  d: path("M16.7 10.3c-5.6-2.7-9.2-8.1-9.2-8.1c-1.5 14.4 4.3 17.9 7.7 18c4.4 0 7.9-6.8 1.5-9.9m30.6 0c5.6-2.7 9.2-8.1 9.2-8.1c1.5 14.4-4.3 17.9-7.7 18c-4.4 0-7.9-6.8-1.5-9.9");
}

.vxz8xgbto {
  fill: var(--svg-color--493b30, #493b30);
}

.xrle-unhp {
  fill: var(--svg-color--493b30, #493b30);
  d: path("M17.3 43.3c2.5 1.5 4.9 2.3 7.3 2.9s4.9.8 7.4.8s4.9-.3 7.4-.8c2.4-.6 4.8-1.5 7.3-2.9c-1.1 2.7-3.4 4.9-6 6.2c-2.7 1.4-5.7 2-8.6 2c-3 0-6-.7-8.6-2c-2.8-1.3-5.1-3.5-6.2-6.2");
}

</style>
