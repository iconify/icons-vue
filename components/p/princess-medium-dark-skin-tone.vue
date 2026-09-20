<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="si06zb6su"/><path class="ryxc10b_r"/><path class="n-0c3yipn"/><path class="ibqze3mkp"/><path class="ry88vdbpe"/><path class="zcoclr0-z"/><ellipse class="lsmcnwj0y"/><circle class="mt03enb-z"/><circle class="ykkcyibef"/><path class="ys-e07b9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:princess-medium-dark-skin-tone" /></template>
<style>
.ibqze3mkp {
  fill: var(--svg-color--915a34, #915a34);
  d: path("M19 26h-2a1 1 0 1 1 0-2h2a1 1 0 1 1 0 2");
}

.lsmcnwj0y {
  cx: 18px;
  cy: 3.5px;
  fill: var(--svg-color--f1f2f2, #f1f2f2);
  rx: 1px;
  ry: 1.5px;
}

.mt03enb-z {
  cx: 14px;
  cy: 4px;
  r: 1px;
  fill: var(--svg-color--f1f2f2, #f1f2f2);
}

.n-0c3yipn {
  fill: var(--svg-color--df1f32, #df1f32);
  d: path("M18 31c-2.347 0-3.575-1.16-3.707-1.293a.999.999 0 0 1 1.404-1.424c.051.047.806.717 2.303.717c1.519 0 2.273-.69 2.305-.719a1.006 1.006 0 0 1 1.408.029a.994.994 0 0 1-.006 1.397C21.575 29.84 20.347 31 18 31");
}

.ry88vdbpe {
  fill: var(--svg-color--60352a, #60352a);
  d: path("M3.064 25c-.03-.325-.064-.647-.064-1c0-5 3 .562 3-3s2-4 4-6l3-3s5 3 9 3s8 2 8 6s3-2 3 3c0 .355-.033.673-.058 1h1.049C34 23.523 34 21.868 34 20C34 7 24 2 18 2S2 7 2 20c0 1.158-.028 2.986.012 5z");
}

.ryxc10b_r {
  fill: var(--svg-color--af7e57, #af7e57);
  d: path("M6 19.562c0-8.526 5.373-15.438 12-15.438s12 6.912 12 15.438S24.627 35 18 35S6 28.088 6 19.562");
}

.si06zb6su {
  fill: var(--svg-color--60352a, #60352a);
  d: path("M18 4c6 0 16 3 16 16s0 16-3 16s-7-3-13-3s-9.915 3-13 3c-3.343 0-3-12-3-16C2 7 12 4 18 4");
}

.ykkcyibef {
  cx: 22px;
  cy: 4px;
  r: 1px;
  fill: var(--svg-color--f1f2f2, #f1f2f2);
}

.ys-e07b9r {
  fill: var(--svg-color--60352a, #60352a);
  d: path("M13 23a1 1 0 0 1-1-1v-2a1 1 0 1 1 2 0v2a1 1 0 0 1-1 1m10 0a1 1 0 0 1-1-1v-2a1 1 0 1 1 2 0v2a1 1 0 0 1-1 1");
}

.zcoclr0-z {
  fill: var(--svg-color--a7a9ac, #a7a9ac);
  d: path("M8 6h20V5l-3-1l-2-3l-3 1l-2-2l-2 2l-3-1l-2 3l-3 1z");
}

</style>
