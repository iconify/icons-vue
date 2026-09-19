<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="qm7pesb5s"/><circle class="ketqe1bnq"/><g class="n1mjunbsu"><path class="a46mypb8f"/><circle class="xvjb8ubav"/></g><path class="bdq_s5d4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:no-pedestrians" /></template>
<style>
.a46mypb8f {
  d: path("m42 47.2l-3.9-9.3c-.3-.8-.5-3.2-.5-3.2c0-.3-.1-.5-.1-.8l-2.3-8.8l3 1.5v2.8c0 .9.7 1.6 1.6 1.6s1.6-.7 1.6-1.6v-4.8L33 20.3c-.5-.3-1.1-.4-1.8-.4c-1.2 0-2.3.5-3.1 1.4l-4 4.1h-5c-.9 0-1.6.7-1.6 1.6s.7 1.6 1.6 1.6h6.3l2.3-2.3l1.5 6.7l-4.1 4.2v10.5c0 .9.7 1.6 1.6 1.6s1.6-.7 1.6-1.6v-9.2l3.3-3.4c.3-.3.7-.5 1.1-.5c.6 0 1.2.4 1.4.9l5.3 12.7c.2.6.8 1 1.5 1c.9 0 1.6-.7 1.6-1.6c-.4 0-.4-.2-.5-.4");
}

.bdq_s5d4t {
  fill: var(--svg-color--ff5a79, #ff5a79);
  d: path("m9.23 13.474l4.243-4.243l41.295 41.295l-4.243 4.242z");
}

.ketqe1bnq {
  cx: 32px;
  cy: 32px;
  r: 24px;
  fill: var(--svg-color--333, #333);
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.qm7pesb5s {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ff5a79, #ff5a79);
}

.xvjb8ubav {
  cx: 29.8px;
  cy: 15.7px;
  r: 2.9px;
}

</style>
