<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="qm7pesb5s"/><circle class="ketqe1bnq"/><path class="ebezvvbke"/><path class="bdq_s5d4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:no-mobile-phones" /></template>
<style>
.bdq_s5d4t {
  fill: var(--svg-color--ff5a79, #ff5a79);
  d: path("m9.23 13.474l4.243-4.243l41.295 41.295l-4.243 4.242z");
}

.ebezvvbke {
  fill: var(--svg-color--fff, #fff);
  d: path("M37.8 15H26.2c-2.1 0-3.8 1.7-3.8 3.8v26.4c0 2.1 1.7 3.8 3.8 3.8h11.5c2.1 0 3.8-1.7 3.8-3.8V18.8c.1-2.1-1.6-3.8-3.7-3.8m-7.7 1.4h3.8c.3 0 .5.2.5.5s-.2.5-.5.5h-3.8c-.3 0-.5-.2-.5-.5s.3-.5.5-.5M32 47.1c-.6 0-1.2-.5-1.2-1.1s.5-1.1 1.2-1.1c.6 0 1.2.5 1.2 1.1s-.6 1.1-1.2 1.1m7.7-4.1H24.3V18.8h15.4z");
}

.ketqe1bnq {
  cx: 32px;
  cy: 32px;
  r: 24px;
  fill: var(--svg-color--333, #333);
}

.qm7pesb5s {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ff5a79, #ff5a79);
}

</style>
