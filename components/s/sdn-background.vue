<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="g279n-gcj"/><path class="dxe9jfsmh"/><path class="w0c1zdb1o"/><path class="yc703292y"/><path class="wj5kghb_k"/><path class="f2b5zu6pf"/><path class="nocexbcac"/><path class="mx9onubdk"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sdn-background" /></template>
<style>
.dxe9jfsmh {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.56 7.125c-7.973 1.653-8.43 4.867-7.658 6.267c-.462-1.102.33-3.747 7.205-5.53z");
}

.f2b5zu6pf {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.4 14.168c.916-1.413.564-2.4.276-2.725c.462 3.503-5.445 5.423-8.458 5.938l-.44.876c2.79-.33 7.484-2.325 8.622-4.09");
}

.ft5dv1b6b {
  fill: none;
}

.g279n-gcj {
  fill: var(--svg-color--bca1e6, #bca1e6);
  d: path("M24 0H0v24h24z");
}

.mx9onubdk {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.907 19.2c.934-.093 3.48-.702 6.178-2.364c2.653-1.64 2.662-3.57 2.325-4.37c.03.587-.423 2.134-2.48 3.645s-5.351 2.298-6.738 2.502l.711.587z");
}

.nocexbcac {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.868 15.782c1.564-2.409-.552-4.689-1.805-5.524c1.943 2.409 2.325 4.222.574 5.902c-1.751 1.689-4.747 2.884-7.423 3.32l.894.52c1.938-.4 6.204-1.804 7.764-4.218z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.w0c1zdb1o {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.6 9.831c-.915 1.414-.564 2.4-.275 2.724c-.463-3.502 5.444-5.422 8.457-5.937l.44-.876c-2.79.33-7.484 2.325-8.622 4.09");
}

.wj5kghb_k {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.093 4.8c-.933.093-3.48.702-6.178 2.364c-2.653 1.64-2.662 3.57-2.324 4.369c-.031-.587.422-2.133 2.48-3.644s5.35-2.298 6.737-2.503l-.71-.586zM6.44 16.876c7.973-1.653 8.431-4.867 7.658-6.267c.462 1.103-.33 3.747-7.205 5.53z");
}

.yc703292y {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.134 8.218c-1.565 2.409.551 4.689 1.804 5.524c-1.942-2.409-2.324-4.222-.573-5.902c1.751-1.689 4.747-2.884 7.422-3.32L15.894 4c-1.938.4-6.205 1.804-7.765 4.218z");
}

</style>
